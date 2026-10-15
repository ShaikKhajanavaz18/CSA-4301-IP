
<!DOCTYPE html>
<html>
<head>
    <title>Library Management System</title>
</head>
<body>
    <h1>Library Management System</h1>
    <hr>

    <h2>Student Login</h2>
    <form>
        Username: <input type="text" required><br><br>
        Password: <input type="password" required><br><br>
        <button type="button">Login</button>
    </form>

    <h2>Book Search</h2>
    <input type="text" placeholder="Enter book name">
    <button type="button">Search</button>

    <h2>Book Details</h2>
    <table border="1" cellpadding="8">
        <tr>
            <th>Book ID</th>
            <th>Book Name</th>
            <th>Status</th>
        </tr>
        <tr>
            <td>101</td>
            <td>Python Programming</td>
            <td>Available</td>
        </tr>
        <tr>
            <td>102</td>
            <td>Database Management</td>
            <td>Issued</td>
        </tr>
    </table>

    <h2>Borrow History</h2>
    <p>Issue Date: 01-10-2026</p>
    <p>Expected Return Date: 15-10-2026</p>

    <h2>Fine Details</h2>
    <p>Fine Amount: Rs. 0</p>

    <h2>Study Materials</h2>
    <p>Year: III | Semester: V</p>
    <a href="notes.pdf" download>Download Study Material</a>

    <h2>Contact Us</h2>
    <form>
        Name: <input type="text" required><br><br>
        Email: <input type="email" required><br><br>
        Message: <textarea required></textarea><br><br>
        <button type="button">Submit</button>
    </form>
</body>
</html>
