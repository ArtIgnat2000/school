/* Общие стили */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f9f9f9;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header */
header {
    background-color: #4CAF50;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header .logo {
    width: 100px;
    height: auto;
    margin-bottom: 10px;
}

header h1 {
    margin: 0;
}

.menu {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 10px;
}

.menu a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.menu a:hover {
    text-decoration: underline;
}

/* Section */
.section {
    padding: 40px 0;
}

.section h2 {
    text-align: center;
    margin-bottom: 20px;
}

.course-list {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.course-item {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    width: calc(33% - 20px);
    text-align: center;
    transition: transform 0.3s ease;
}

.course-item:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

@media (max-width: 768px) {
    .course-item {
        width: 100%;
    }
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 40px;
}
