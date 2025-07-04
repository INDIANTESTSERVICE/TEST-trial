<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>History of HTML - MCQ Quiz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            background-color: #f9f9f9;
        }
        h1 {
            text-align: center;
        }
        .question {
            margin-bottom: 20px;
            background: #ffffff;
            padding: 15px;
            border: 1px solid #ccc;
            border-radius: 8px;
        }
        .options {
            margin-top: 10px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
    </style>
</head>
<body>

<h1>History of HTML - Multiple Choice Questions</h1>

<!-- Question Format Example -->
<div class="question">
    <p><strong>1. Who is known as the inventor of HTML?</strong></p>
    <div class="options">
        <label><input type="radio" name="q1"> Tim Berners-Lee</label>
        <label><input type="radio" name="q1"> Bill Gates</label>
        <label><input type="radio" name="q1"> Steve Jobs</label>
        <label><input type="radio" name="q1"> Larry Page</label>
    </div>
</div>

<!-- Repeat for 30 questions -->

<!-- Questions 2 to 30 -->
<script>
    const questions = [
        "In which year was HTML first proposed?",
        "What does HTML stand for?",
        "Which organization is responsible for maintaining HTML standards?",
        "Which version of HTML introduced semantic elements like <article>, <section>, and <nav>?",
        "What was the initial purpose of HTML?",
        "HTML was initially developed at which institution?",
        "What is the name of the first web browser?",
        "HTML is a type of:",
        "Which of these is a deprecated HTML tag?",
        "Which HTML version came before HTML5?",
        "What language influenced the design of HTML?",
        "What was the major goal of HTML5?",
        "When was HTML5 officially released?",
        "HTML 4.01 was released in which year?",
        "Who maintains the HTML specification today?",
        "What does W3C stand for?",
        "The first HTML specification was called:",
        "HTML is considered a subset of which larger markup language?",
        "What was the initial number of HTML tags in version 1.0?",
        "Which browser first supported HTML5 features?",
        "What is the role of the <doctype> declaration in HTML?",
        "Which HTML version was the first to support CSS?",
        "When was HTML 2.0 released?",
        "HTML4 introduced support for:",
        "HTML5 was developed as a collaboration between which two major groups?",
        "Which element was introduced in HTML5 to embed video content?",
        "What does the <abbr> tag represent in HTML?",
        "What is the role of the <meta> tag in HTML documents?",
        "Which version of HTML introduced support for scripting languages like JavaScript?",
        "HTML evolved from which early markup language used at CERN?"
    ];

    const options = [
        ["1991", "1995", "2000", "1989"],
        ["Hyper Text Markup Language", "Hyperlink and Text Markup Language", "Home Tool Markup Language", "Hyper Transfer Markup Language"],
        ["W3C", "Google", "Apple", "Microsoft"],
        ["HTML5", "HTML4", "HTML 3.2", "HTML 2.0"],
        ["Linking documents", "Building apps", "Creating games", "Developing software"],
        ["CERN", "MIT", "NASA", "Stanford"],
        ["WorldWideWeb", "Mosaic", "Netscape", "Opera"],
        ["Markup Language", "Programming Language", "Style Sheet Language", "Database Language"],
        ["<font>", "<p>", "<h1>", "<div>"],
        ["HTML 4.01", "HTML 3.2", "XHTML", "HTML2"],
        ["SGML", "XML", "CSS", "JSON"],
        ["Rich media support", "Faster loading", "Simpler syntax", "Lower latency"],
        ["2014", "2010", "2008", "2016"],
        ["1999", "1996", "2001", "2003"],
        ["WHATWG", "W3C", "HTML Inc.", "Mozilla Foundation"],
        ["World Wide Web Consortium", "Web Wide Web Collaboration", "World Web Code", "World Web Chart"],
        ["HTML Tags v0.9", "HTML Tags v1.0", "HTML Internet", "HTML Draft"],
        ["SGML", "XML", "Markdown", "YAML"],
        ["18", "20", "22", "12"],
        ["Chrome", "Internet Explorer", "Firefox", "Safari"],
        ["Declares HTML version", "Starts the page", "Displays metadata", "Defines comments"],
        ["HTML 4.0", "HTML 3.2", "HTML 2.0", "HTML5"],
        ["1995", "1994", "1996", "1997"],
        ["CSS integration", "Mobile support", "Plugins", "Tables"],
        ["W3C and WHATWG", "W3C and Google", "W3C and Apple", "WHATWG and Microsoft"],
        ["<video>", "<media>", "<movie>", "<player>"],
        ["Abbreviation", "Abstract", "Anchor", "Append"],
        ["SEO optimization", "Document metadata", "Text styling", "Form validation"],
        ["HTML 3.2", "HTML4", "HTML5", "HTML2"],
        ["SGML", "XML", "LaTeX", "DocBook"]
    ];

    const container = document.body;

    for (let i = 0; i < questions.length; i++) {
        const div = document.createElement("div");
        div.className = "question";

        const questionHTML = `<p><strong>${i + 2}. ${questions[i]}</strong></p>`;
        div.innerHTML = questionHTML;

        const optionsHTML = options[i].map(opt =>
            `<label><input type="radio" name="q${i + 2}"> ${opt}</label>`
        ).join('');

        const optionsContainer = document.createElement("div");
        optionsContainer.className = "options";
        optionsContainer.innerHTML = optionsHTML;

        div.appendChild(optionsContainer);
        container.appendChild(div);
    }
</script>

</body>
</html>

