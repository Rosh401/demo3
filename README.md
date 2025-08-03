# demo3
<html lang="en">
    <head>
        <title>Feedback Form</title>
        <style>
            body{
                font-family: Arial, Helvetica, sans-serif;
                background-color: gray;
                margin: 0;
                height: 100vh;
                justify-content: center;
                flex-wrap: wrap;
                align-items: center;
                display: flex;
            }
            .Feedback-box{
                background-color: lightgray;
                padding: 20px;
                box-shadow: 0 0 10px rgba(0,0,0,1.0);
                width: 300px;
                border-radius: 8px;
            }
            h2{
                text-align: center;
                color:#333;
                margin-top: 0;
            }
            input , textarea{
                margin: 8px 0;
                padding: 8px;
                width: 100%;
                border: 1px solid #ddd;
                border-radius: 4px;
            }
            button{
                width: 100%;
                padding: 10px;
                background: green;
                color: white;
                border: none;
                border-radius: 4px;
                cursor: pointer;
            }
            button :hover{
                background-color: green;
                padding: 8px;
                
            }
        </style>
        <body>
            <div class="Feedback-box">
                <h2>Feedback</h2>
                <input type="text" placeholder="Your Name">
                <input type="Email" placeholder="Your Email">
                <input type="Experience" placeholder="Your Experience">
                <textarea rows="4" placeholder="Your feedback"></textarea>
                <button onclick="Myfun()">Submit Feedback</button>
                <script>
                    function Myfun(){
                        alert("Submitted Feedback Successfully");
                    }
                </script>
            </div>
        </body>
    </head>
</html>
