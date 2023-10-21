# RG18-pet-adoption
1. Web Development Basics 1 - 18. Module Assessment - PET ADOPTION

## Instructions
1. Create a folder for the project on your computer with the name "pet-adoption".

2. Create an HTML file called index.html inside the pet-adoption folder using visual studio code editor and paste the following codes into it.
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Robogarden Pet Shelter</title>

        <style>
            table, td, th {
                border: 1px solid black;
            }
        </style>
    </head>

    <body>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="adopt.html">Adopt a Pet</a></li>
        </ul>

        <h1>Welcome to Robogarden Pet Shelter</h1>
        <p>We serve as home for hundreds of pets.</p>

        <table>
            <caption>Robogarden Shelter Pets</caption>
            <tr>
                <th>ID Number</th>
                <th>Picture</th>
                <th>Breed</th>
                <th>Name</th>
                <th>Age</th>
                <th>Gender</th>                
            </tr>

            <tr>
                <td>001</td>
                <td><img src="https://www.prestigeanimalhospital.com/sites/default/files/styles/large/adaptive-image/public/siberian-husky-dog-breed-info.jpg?itok=hEp0uepN" width="80" ></td>
                <td>Husky</td>
                <td>Bruno</td>
                <td>4</td>
                <td>Male</td>
            </tr>

            <tr>
                <td>002</td>
                <td><img src="https://www.prestigeanimalhospital.com/sites/default/files/styles/large/adaptive-image/public/labrador-retriever-dog-breed-info.jpg?itok=WarwMXBC" width="80" ></td>
                <td>Labrador</td>
                <td>Jenny</td>
                <td>2</td>
                <td>Female</td>
            </tr>

            <tr>
                <td>003</td>
                <td><img src="https://www.prestigeanimalhospital.com/sites/default/files/styles/large/adaptive-image/public/golden-retriever-dog-breed-info.jpg?itok=scGfz-nI" width="80" ></td>
                <td>Golden Retriever</td>
                <td>Paulo</td>
                <td>8</td>
                <td>Male</td>
            </tr>
        </table>
    </body>
</html>
```

3. Create another HTML file called adopt.html inside the pet-adoption folder using visual studio code editor and paste the following codes into adopt.html.
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Robogarden Pet Shelter</title>
    </head>

    <body>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="adopt.html">Adopt a Pet</a></li>
        </ul>

        <h1>Adopt a Pet</h1>
        <p>Fill the form below to apply for pet adoption.</p>

        <form>
            <p>
                <label>Pet ID Number</label>
                <input type="text">            
            </p>

            <p>
                <label>Your Name</label>
                <input type="text">
            </p>

            <p>
                <label>Phone number</label>
                <input type="tel">
            </p>

            <p>
                <label>Email</label>
                <input type="email">
            </p>

            <button type="submit">Submit</button>
        </form>
    </body>
</html>
```

4. Upload your project to GitHub.

5. Submit Your GitHub Link
