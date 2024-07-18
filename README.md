<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/style.css">
    <title>Document</title>
</head>
<body>
    <div>
        <img src="https://images.unsplash.com/photo-1668625597153-bbce4d21ebec?q=80&w=1887&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="" class="right-side-pic">
    </div>
    <div class="about-text">
         <h2>This is not a real online service! You know you need something like
          this in your life to help you realize your deepest dreams. Sign up
          <em>now</em> to get started.</h2>
        <h3>You <span>know</span> you want to.</h3>
      </div>
      <form action="" method="get" class="customer-form">
        <div class='form-row'>
            <label for='full-name'>FIRST NAME</label>
            <input id='full-name' name='full-name' type='text'/>
          </div>
          <div class='form-row'>
            <label for='last-name'>LAST NAME</label>
            <input id='last-name' name='last-name' type='text'/>
          </div>
          <div class='form-row'>
            <label for='email'>EMAIL</label>
            <input id='email' name='email' type='email'/>
          </div>
          <div class='form-row'>
            <label for='phone-number'>PHONE NUMBER</label>
            <input id='phone-number' name='phone-number' type='number'/>
          </div>
          <div class='form-row'>
            <label for='password'>PASSWORD</label>
            <input id='password' name='password' type='password'/>
          </div>
          <div class='form-row'>
            <label for='confirm-password'>CONFIRM PASSWORD</label>
            <input id='confirm-password' name='password' type='password'/>
          </div>
      </form>
      <button class="btn">Create Account</button>
      <p class="footer">Already have an account? <a href="">Log in</a></p>
</body>
</html>

css

* {
    margin: 0;
    padding: 0;
}

.right-side-pic {
    display: flex;
    height: 100vh;
    width:30vw;
    background-image: url(https://cdn.statically.io/gh/TheOdinProject/curriculum/5f37d43908ef92499e95a9b90fc3cc291a95014c/html_css/project-sign-up-form/odin-lined.png);
    float: left;
}

.about-text {
    font-weight: 600;
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding:80px 20px 40px 20px;
}

.customer-form {
    background-color: #f6f7f8;
    border: 1px solid #d6d9dc;
    border-radius: 3px;

    font-size: x-small;
    font-weight: bolder;

    width: 50%;
    height: 250px;
    padding:20px;
    margin-left: 400px;
    display: flex;
    flex-wrap: wrap; /* Allow wrapping */
    gap: 14px;
}

.form-row {
    display: flex;
    justify-content: center;
    flex-direction: column;
    flex-wrap: wrap;
    gap: 14px;
    margin-bottom: 0px;
}

.form-row input {
    background-color: #FFFFFF;
    border: 1px solid #E5E7EB;
    border-radius: 3px;
    width: 70%;
    padding: 2px;
    font-size: 14px;
    display: flex;
    justify-content: center;
    margin-right: 100px;
  }
  
  .form-row label {
    margin:0;
  }

  input:invalid {
  border: 1px solid red;
}

  input:valid {
  border: 1px solid green;
} 

.btn {
    background-color: #596D48;
    color: white;
    padding: 10px;
    border: 2px solid #5D6063;
    border-radius: 6px; 
    width: 200px;
    margin: 5px 0px 5px 15px;
}

.footer {
    display: flex;
    margin: 5px 0px 5px 400px;
}
