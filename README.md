# html-repo
<html>
<head>
<title> Login Page </title>
<style>
Body {
  font-family: Calibri;
  background-color: gray;
}
</style>
</head>
<body>
    <center> <h1> Student Login Form </h1> </center>
    <form>
        <div class="container">
            <label>Username : </label>
            <input type="text" placeholder="Enter Username" name="username" required><br/>
            <label>Password : </label>
            <input type="password" placeholder="Enter Password" name="password" required><br/>
            <button type="submit">Login</button>   <br/>
            <input type="checkbox" checked="checked"> Remember me
            <button type="button" class="cancelbtn"> Cancel</button>
            Forgot <a href="#"> password? </a>
        </div>
    </form>
</body>
</html>
