<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School of Web Dev | Mock Exam</title>
</head>
<body>
    <header>
        <nav>
            <img src="https://res.cloudinary.com/dpyanhld4/image/upload/v1598954330/Migrant/code_dsjmwa.png" width="30" height="30" align="left" alt="Website Icon" />
            <h1>School of Web Dev</h1>
        </nav>
    </header>

    <section id="rules" style="background-color: lightgrey;">
        <h2 style="text-align: center;">Rules for the mock exam</h2>
        <ol>
            <li>Attempt all questions.</li>
            <li>Every correct answer will get you +10 points.</li>
            <li>Every incorrect answer will deduct -2 points from your overall score.</li>
            <li>The form will remain open from 10:00 am - 12:00 pm.</li>
            <li>Late entries will not be accepted at any cost.</li>
            <li>In case of any technical issue or queries, contact contact@school-webdev.com</li>
        </ol>
        <p>ALL THE BEST!</p>
    </section>

    <section id="questions">
        <form action="https://formspree.io/FORM_ID" method="POST">
        <label>
            <h3>Enter your Full Name:</h3>
            <input type="text" name="name" placeholder="Full name here" />
        </label><br>

        <label>
            <h3>Enter you School Email ID:</h3>
            <input type="email" name="email" placeholder="Valid email id here" />
        </label><br>

        <label>
            <h3>How do you identify yourself?</h3>
            <select id="gender">
                <option>Choose...</option>
                <option value="she/her" name="gender">She/Her</option>
                <option value="he/him" name="gender">He/Him</option>
                <option value="other" name="gender">Other</option>
            </select>
        </label><br>
        
        <label id="question1">
            <h3>1. What is full form of IDE?</h3>
            <input type="radio" value="option1" name="question1" /> Internet Development Environment.
            <input type="radio" value="option2" name="question1" /> Integrated Development Environment.
            <input type="radio" value="option3" name="question1" /> Intelligent Development Environment.
            <input type="radio" value="option4" name="question1" /> None of the mentioned above.
        </label><br>

        <label id="question2">
            <h3>2. How do you link CSS files in HTML?</h3>
            <input type="radio" value="option1" name="question2" /> Using meta tag
            <input type="radio" value="option2" name="question2" /> Using header tag
            <input type="radio" value="option3" name="question2" /> Using script tag
            <input type="radio" value="option4" name="question2" /> Using link tag
        </label><br>

        <label id="question3">
            <h3>3. What is the difference between div tag and span tag?</h3>
            <p>Explain in no more than 200 words.</p>
            <textarea name="question3" cols="100" rows="10" maxlength="200" >Enter your answer here...</textarea>
        </label><br>

        <label id="question4">
            <h3>4. What is the difference between class and id?</h3>
            <p>Explain in no more than 200 words.</p>
            <textarea name="question4" cols="100" rows="10" maxlength="200">Enter your answer here...</textarea>
        </label><br>  
        
        <label id="question5">
            <h3>5. How do you make your website SEO friendly (Mention tags used for adding keywords and description for your website)?</h3>
            <p>Explain in no more than 200 words.</p>
            <textarea name="question5" cols="100" rows="10" maxlength="200">Enter your answer here...</textarea>
        </label><br>

        <label id="question6">
            <h3>6. Which tags are used for date and units like format (For e.g. 24<sup>th</sup> Feb 2019 and 10<sub>2</sub> = 2<sub>10</sub>).</h3>
            <textarea name="question6" cols="100" rows="10">Enter your answer here...</textarea>
        </label><br>

        <label id="question7">
            <h3>7. Which tag is used for numbered lists in HTML?</h3>
            <input type="radio" value="option1" name="question7" /> ol tag
            <input type="radio" value="option2" name="question7" /> ul tag
            <input type="radio" value="option3" name="question7" /> li tag
            <input type="radio" value="option4" name="question7" /> a tag
        </label><br>

        <label id="question8">
            <h3>8. Which heading elements are allowed in HTML from following options?</h3>
            <input type="checkbox" value="option1" name="question8" /> h4
            <input type="checkbox" value="option2" name="question8" /> h5
            <input type="checkbox" value="option3" name="question8" /> h6
            <input type="checkbox" value="option4" name="question8" /> h7
        </label><br>

        <label id="question9">
            <h3>9. Which of the following attributes is used to add link to any element?</h3>
            <input type="radio" value="option1" name="question9" /> link
            <input type="radio" value="option2" name="question9" /> src
            <input type="radio" value="option3" name="question9" /> href
            <input type="radio" value="option4" name="question9" /> vlink
        </label><br>

        <label id="question10">
            <h3>10. Write short note on any HTML tag of your choice in atleast 500 words.</h3>
            <textarea name="question10" cols="100" rows="10" maxlength="200">Enter your answer here...</textarea>
        </label><br><br>

        <input type="submit" value="Send">
        </form>
    </section>

    <footer>
        <h3>Hope you completed all questions. Thank you for being here! See you in final exam.</h3>
    </footer>

</body>
</html>
