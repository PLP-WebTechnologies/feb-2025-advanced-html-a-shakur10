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

Happy Coding! 💻✨





<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bafana Bafana Football Academy Registration</title>
</head>
<body>

  <header>
    <h1>Welcome to Bafana Bafana Football Club Academy</h1>
    <p>Join one of the top youth football academies in Kenya!</p>
  </header>

  <h3>Academy Training Modules</h3>
<ol type="I">
  <li>Fitness & Conditioning</li>
  <li>Ball Control & Passing</li>
  <li>Positioning & Tactics</li>
  <li>Match Simulations</li>
  <li>Team Building & Leadership</li>
</ol>
  </section>

  <section>
    <h2>Football Action!</h2>
    <img src="https://images.pexels.com/photos/114296/pexels-photo-114296.jpeg"
         alt="Football training" width="600" />
  </section>

  <section>
    <h2>Registered Young Stars</h2>
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
          <td>Abdi Musa</td>
          <td>Tullu Roba, Isiolo</td>
          <td>+254701111111</td>
          <td>abdi.musa@example.com</td>
        </tr>
        <tr>
          <td>Hassan Noor</td>
          <td>Mjini, Meru</td>
          <td>+254702222222</td>
          <td>hassan.noor@example.com</td>
        </tr>
        <tr>
          <td>Salim Yusuf</td>
          <td>Bulla Pesa, Isiolo</td>
          <td>+254703333333</td>
          <td>salim.yusuf@example.com</td>
        </tr>
        <tr>
          <td>Ali Ibrahim</td>
          <td>Mitunguu, Meru</td>
          <td>+254704444444</td>
          <td>ali.ibrahim@example.com</td>
        </tr>
        <tr>
          <td>Jamal Ahmed</td>
          <td>Wabera, Isiolo</td>
          <td>+254705555555</td>
          <td>jamal.ahmed@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section>
    <h2>Join the Academy</h2>
    <form action="#" method="POST">

      <label for="name">Full Name:</label><br />
      <input type="text" id="name" name="name" placeholder="Enter your full name" required /><br /><br />

      <label for="email">Email Address:</label><br />
      <input type="email" id="email" name="email" placeholder="example@mail.com" required /><br /><br />

      <label for="password">Create Password:</label><br />
      <input type="password" id="password" name="password" placeholder="Min. 6 characters" minlength="6" required /><br /><br />

      <label for="dob">Date of Birth:</label><br />
      <input type="date" id="dob" name="dob" required /><br /><br />

      <label for="position">Preferred Playing Position:</label><br />
      <select id="position" name="position" required>
        <option value="">--Select Position--</option>
        <option value="goalkeeper">Goalkeeper</option>
        <option value="defender">Defender</option>
        <option value="midfielder">Midfielder</option>
        <option value="forward">Forward</option>
      </select><br /><br />

      <label>Footedness:</label><br />
      <input type="radio" id="left" name="foot" value="left" required />
      <label for="left">Left-footed</label><br />
      <input type="radio" id="right" name="foot" value="right" />
      <label for="right">Right-footed</label><br /><br />

      <label>Available Days for Training:</label><br />
      <input type="checkbox" id="mon" name="days" value="Monday" />
      <label for="mon">Monday</label><br />
      <input type="checkbox" id="wed" name="days" value="Wednesday" />
      <label for="wed">Wednesday</label><br />
      <input type="checkbox" id="fri" name="days" value="Friday" />
      <label for="fri">Friday</label><br /><br />

      <input type="submit" value="Register Now" />
    </form>
  </section>

  <section>
    <h2>Club Anthem 🎶</h2>

    <audio controls>
      <source src="https://audio.com/sharon-stiles/audio/football-motivation-taster/download" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
    <br /><br />

    <h3>Football Highlights</h3>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/7BAnleA_Vkc" title="YouTube football video" frameborder="0" allowfullscreen></iframe>
  </section>

  <footer>
    <p>&copy; 2025 Bafana Bafana Football Club Academy. All rights reserved.</p>
  </footer>

</body>
</html>



