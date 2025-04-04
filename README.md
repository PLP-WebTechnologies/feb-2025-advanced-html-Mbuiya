# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML5 Example</title>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List of Roman Numerals</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
            <li>Fifth Item</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Beautiful Landscape</h2>
        <img src="https://images.pexels.com/photos/1048277/pexels-photo-1048277.jpeg" alt="Beautiful Landscape" width="600">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact List</h2>
        <table border="1" cellpadding="10">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Doe</td>
                    <td>123 Main St, City</td>
                    <td>(123) 456-7890</td>
                    <td>johndoe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak Rd, City</td>
                    <td>(987) 654-3210</td>
                    <td>janesmith@example.com</td>
                </tr>
                <tr>
                    <td>Sam Brown</td>
                    <td>789 Pine Ln, City</td>
                    <td>(555) 123-4567</td>
                    <td>sambrown@example.com</td>
                </tr>
                <tr>
                    <td>Lucy Green</td>
                    <td>321 Elm St, City</td>
                    <td>(444) 987-6543</td>
                    <td>lucygreen@example.com</td>
                </tr>
                <tr>
                    <td>Mark White</td>
                    <td>654 Birch Ave, City</td>
                    <td>(333) 555-6789</td>
                    <td>markwhite@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="/submit" method="POST" id="registrationForm">
            <!-- Name Field -->
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>

            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>

            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="6">
            <br><br>

            <!-- Date Field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>

            <!-- Dropdown Field -->
            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="">Select Gender</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
            <br><br>

            <!-- Radio Button -->
            <label>Newsletter Subscription:</label>
            <input type="radio" id="subscribeYes" name="subscribe" value="yes">
            <label for="subscribeYes">Yes</label>
            <input type="radio" id="subscribeNo" name="subscribe" value="no" checked>
            <label for="subscribeNo">No</label>
            <br><br>

            <!-- Checkbox Field -->
            <label for="terms">I agree to the terms and conditions:</label>
            <input type="checkbox" id="terms" name="terms" required>
            <br><br>

            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Multimedia Elements -->
    <section>
        <h2>Multimedia Elements</h2>

        <!-- Audio -->
        <h3>Audio Example</h3>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>

        <!-- Video -->
        <h3>Video Example</h3>
        <video controls width="600">
            <source src="https://www.w3schools.com/html/movie.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>

</body>
</html>


Happy Coding! 💻✨
