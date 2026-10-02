# student-registration
Student details table using HTML and CSS
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration</title>
</head>

<body>

<form action="" method="post" name="registration">

    <p>
        Student name:
        <br>
        <input type="text" name="student name"
               value="Enter your name here" maxlength="50">
    </p>

    <p>
        Age:
        <br>
        <input type="date" id="dob" name="age">
    </p>

    <p>
        Please select your gender:
        <br>
        <input type="radio" name="gender" value="female"> Female
        <input type="radio" name="gender" value="male"> Male
    </p>

    <p>
        ID number:
        <br>
        <input type="text" name="ID number"
               value="Enter your ID number here" maxlength="10">
    </p>

    <p>
        Patient ID:
        <br>
        <input type="text" name="patient ID"
               value="Enter patient Id here" maxlength="10">
    </p>

    <p>
        Phone number:
        <br>
        <input type="text" name="phone number"
               value="Enter your phone number here" maxlength="14">
    </p>

    <p>
        Do you have any disability:
        <br>
        <input type="checkbox" name="disability" value="good">
        Good

        <input type="checkbox" name="disability" value="chronic disease">
        Chronic disease

        <input type="checkbox" name="disability" value="allergies">
        Allergies
    </p>

    <p>
        Address:
        <br>
        <input type="text" name="Address"
               value="Enter your Address here" maxlength="10">
    </p>

    <p>
        Please select your marital status:
        <br>
        <input type="radio" name="marital status" value="married">
        Married

        <input type="radio" name="marital status" value="single">
        Single

        <input type="radio" name="marital status" value="divorced">
        Divorced
    </p>

    <p>
        Please select your next of kin:
        <br>
        <input type="checkbox" name="next of kin" value="mother">
        Mom

        <input type="checkbox" name="next of kin" value="father">
        Father

        <input type="checkbox" name="next of kin" value="daughter">
        Daughter
    </p>

    <p>
        Please select your weight:
        <br>
        <input type="radio" name="weight" value="underweight">
        Underweight

        <input type="radio" name="weight" value="normal">
        Normal

        <input type="radio" name="weight" value="overweight">
        Overweight
    </p>

</form>

</body>
</html>
