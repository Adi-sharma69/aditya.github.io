# aditya.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FORMS-ADITYA SHARMA</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>form to apply for admission in GLA University</h1>
    <form action="post">
        <div>
            <label for="username">Enter your name:-</label>
            <input type="plaintext" id="username" name="username" placeholder="student name" autofocus required>
        </div>
        <br>
        <div>
            <label for="username">Enter your father's name:-</label>
            <input type="plaintext" id="username" name="username" placeholder="father's name" autofocus required>
        </div>
        <br>
        <div>
            <label for="username">Enter your mother's name:-</label>
            <input type="plaintext" id="username" name="username" placeholder="mother's name" autofocus required>
        </div>
        <br>
        <div>    
            <label for="male">Male</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="Female">Female</label>
            <input type="radio" id="Female" name="gender" value="Female" required>
        </div>

        <div>
            <h2>Email id</h2>
            <lable for="email">Enter your email:</lable>
            <input type="email " id="email" name="email" placeholder="enter your email"required>
        </div>
        <br>
        <div>
        <br>
            <h8>Board of Education:</h8>
        <br>
            <select name="Board of Education" required>
                <option value="Central Board of Secondary Education">Central Board of Secondary Education</option>
                <option value="Rajasthan Board of Secondary Education">Rajasthan Board of Secondary Education</option>
                <option value="Indian Certificate of Secondary Education">Indian Certificate of Secondary Education</option>
                <option value="All India Senior School Certificate Examination">All India Senior School Certificate Examination</option>
                <option value="National Institute of Open Schooling">National Institute of Open Schooling</option>
                <option value="Board of High School and Intermediate Education Uttar Pradesh">Board of High School and Intermediate Education Uttar Pradesh</option>
            </select>    
        </div>

        <div>
            <h3>Acedemic qualifications</h3>
            <select name="acdemic qualification">
                <option value="High school plus Inter passed with PCM with CS">High school plus Inter passed with PCM with CS</option>                
                <option value="High school plus passed with PCM with Physical">High school plus passed with PCM with Physical</option>                
                <option value="High school plus passed with PCMB with Physical">High school plus passed with PCMB with Physical</option>                
                <option value="High school plus passed with PCMB with CS">High school plus passed with PCMB with CS</option>                
                <option value="High school plus passed with Commerse with IP">High school plus passed with Commerse with IP</option>                
                <option value="High school plus passed with Arts with Physical">High school plus passed with Arts with Physical</option>                             
            </select>
        </div>

        <div>
            <h4>Date of Birth</h4> 
            <label for="birthday">Birthday</label>
            <Input type="date" id="birthday" name="birthday"required>
        </div>
        
        <div>
            <h5>Student contact no.</h5>
            <label for="phone">Enter your contact number:</label>
            <input type="tel" id="phone" name="phone" placeholder="123-4567-890" pattern="[0-9]{3}-[0-9]{3}"required>
        </div>

        <div>
            <h6>Caste</h6>
            <select name="Caste" required>
                <option value="Generel Category">Generel Category</option>
                <option value="Shedule tribe">Shedule tribe</option>
                <option value="Shedule caste">Shedule caste</option>
                <option value="Other backw reard caste">Other backward caste</option>
            </select>            
        </div>        

        <div>

        <br>

            <h7>High School marksheet</h7>
        <br>    
        <br>
            <label for="myfile">select a file:</label>
            <input type="file" id="myfile" name="myfile" required>
        </div>
        <br>
        <div>
            <input type="Submit" value="Submit">
            <input type="Reset" value="Reset">
        </div>

    </form>
</body>
</html>

