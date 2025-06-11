<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Student Section Finder</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 500px;
      margin: 50px auto;
      padding: 20px;
    }
    input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      font-size: 16px;
    }
    .result {
      font-size: 18px;
      font-weight: bold;
      color: green;
    }
    .not-found {
      color: red;
    }
  </style>
</head>
<body>
  <h2>Find Your Section</h2>
  <input type="text" id="searchInput" placeholder="Enter your full name" />
  <div id="output" class="result"></div>

  <script>
    const students = [
      { name: "Almonte Kevin James", section: "Grade 11- Aristotle" },
      { name: "Apura Lourence", section: "Grade 11- Aristotle" },
      { name: "Baang Kent Nathaniele", section: "Grade 11- Aristotle" },
      { name: "Bacon Denielle Jake", section: "Grade 11- Aristotle" },
      { name: "Dayanan Cristof", section: "Grade 11- Aristotle" },
      { name: "Fernandez John Mark", section: "Grade 11- Aristotle" },
      { name: "Gako Christian", section: "Grade 11- Aristotle" },
      { name: "Irona Dave", section: "Grade 11- Aristotle" },
      { name: "Lauron Christian", section: "Grade 11- Aristotle" },
      { name: "Lausa BB Jenboy", section: "Grade 11- Aristotle" },
      { name: "Lu- ang Richard Dems", section: "Grade 11- Aristotle" },
      { name: "Pantilgan Jackris", section: "Grade 11- Aristotle" },
      { name: "Remo Criss Michol", section: "Grade 11- Aristotle" },
      { name: "Satinitigan June Vincent", section: "Grade 11- Aristotle" },
      { name: "Tangaro Negro Patrick", section: "Grade 11- Aristotle" },
      { name: "Tumulak Kienneth", section: "Grade 11- Aristotle" },
      { name: "Ygona Ansel", section: "Grade 11- Aristotle" },
      { name: "Amistad Mary Cris", section: "Grade 11- Aristotle" },
      { name: "Cabungcal Nechel Mae", section: "Grade 11- Aristotle" },
      { name: "Cabungcal Krisha Marie", section: "Grade 11- Aristotle" },
      { name: "Dela Cerna Samantha", section: "Grade 11- Aristotle" },
      { name: "Enad Sweet Kiel", section: "Grade 11- Aristotle" },
      { name: "Erezo Kristel", section: "Grade 11- Aristotle" },
      { name: "Espinosa Angelie", section: "Grade 11- Aristotle" },
      { name: "Larrobis Glyza Mar", section: "Grade 11- Aristotle" },
      { name: "Lauron Shane", section: "Grade 11- Aristotle" },
      { name: "Legarte Jhilia Mie", section: "Grade 11- Aristotle" },
      { name: "Liniojan Beverly", section: "Grade 11- Aristotle" },
      { name: "Mortifero Shane", section: "Grade 11- Aristotle" },
      { name: "Navarro Chiecky Jayne", section: "Grade 11- Aristotle" },
      { name: "Naveo Maria Ivonne", section: "Grade 11- Aristotle" },
      { name: "Navoa Kisha Mae", section: "Grade 11- Aristotle" },
      { name: "Pansan Fhebe Gail", section: "Grade 11- Aristotle" },
      { name: "Parame Kylla", section: "Grade 11- Aristotle" },
      { name: "Rudila Zairra", section: "Grade 11- Aristotle" },
      { name: "Sabala Rhia Madjih", section: "Grade 11- Aristotle" },
      { name: "Tangaro Ella Mae", section: "Grade 11- Aristotle" }
    ];

    document.getElementById("searchInput").addEventListener("input", function () {
      const input = this.value.trim().toLowerCase();
      const output = document.getElementById("output");

      const match = students.find(s => s.name.toLowerCase() === input);

      if (input === "") {
        output.textContent = "";
      } else if (match) {
        output.textContent = `${match.name} is enrolled in ${match.section}`;
        output.className = "result";
      } else {
        output.textContent = "Name not found. Please check your spelling.";
        output.className = "result not-found";
      }
    });
  </script>
</body>
</html>
