
<!DOCTYPE html>
<html>
<head>
    <title>Online Bus Ticket Booking</title>
</head>
<body>
    <h1>Online Bus Ticket Booking System</h1>
    <hr>

    <h2>User Registration</h2>
    <form>
        Name: <input type="text" required><br><br>
        Email: <input type="email" required><br><br>
        Password: <input type="password" required><br><br>
        <button type="button">Register</button>
    </form>

    <h2>User Login</h2>
    <form>
        Username: <input type="text" required><br><br>
        Password: <input type="password" required><br><br>
        <button type="button">Login</button>
    </form>

    <h2>Search Bus</h2>
    <form>
        Source:
        <input type="text" placeholder="From" required><br><br>
        Destination:
        <input type="text" placeholder="To" required><br><br>
        Journey Date:
        <input type="date" required><br><br>
        Bus Type:
        <select>
            <option>Volvo</option>
            <option>Sleeper Coach</option>
            <option>Ordinary Coach</option>
        </select><br><br>
        <button type="button">Search Bus</button>
    </form>

    <h2>Available Buses</h2>
    <table border="1" cellpadding="8">
        <tr>
            <th>Bus No.</th>
            <th>Bus Name</th>
            <th>Departure</th>
            <th>Seats</th>
            <th>Price</th>
        </tr>
        <tr>
            <td>101</td>
            <td>Express Volvo</td>
            <td>09:00 AM</td>
            <td>20</td>
            <td>Rs. 800</td>
        </tr>
        <tr>
            <td>102</td>
            <td>Night Sleeper</td>
            <td>10:00 PM</td>
            <td>15</td>
            <td>Rs. 1000</td>
        </tr>
    </table>

    <h2>Book Ticket</h2>
    <form>
        Passenger Name: <input type="text" required><br><br>
        Age: <input type="number" min="1" required><br><br>
        Seat Number: <input type="number" min="1" required><br><br>
        <button type="button">Book Ticket</button>
    </form>

    <h2>Cancel Ticket</h2>
    Booking ID: <input type="text">
    <button type="button">Cancel Booking</button>

    <h2>Comments</h2>
    <textarea placeholder="Write your comments"></textarea><br><br>
    <button type="button">Submit Comment</button>

    <h2>Admin Panel</h2>
    <p>Manage bus categories, bus details, schedules, seats, and users.</p>
    <button type="button">Generate Report</button>

    <h2>Forgot Password</h2>
    <input type="email" placeholder="Enter registered email">
    <button type="button">Reset Password</button>

    <footer>
        <hr>
        <p>&copy; 2026 Online Bus Ticket Booking System</p>
    </footer>
</body>
</html>
