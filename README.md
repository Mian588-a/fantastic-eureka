<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Form</title>
<link rel="stylesheet" href="style.css">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<link href="https://cdn.jsdelivr.net/npm/remixicon@4.6.0/fonts/remixicon.css" rel="stylesheet">
</head>
<body>

  <div class="noise-layer" id="noise"></div>
<div class="vignette"></div>

<div class="card-wrap">

    <div class="card">

        <button class="close-btn" aria-label="Close">✕</button>

        <!-- Tabs -->

        <div class="auth-tabs">

            <button class="tab active" id="signupTab">
                Sign Up
            </button>

            <button class="tab" id="loginTab">
                Login
            </button>
    
    </div>

    <h1 class="title" id="title">
      Create Account
  </h1>
      

      <div class="divider"></div>
  <!-- ========================= -->
<!-- SIGN UP FORM -->
<!-- ========================= -->


<form id="signupForm" autocomplete="off">

  <div class="input-row">

      <input
          type="text" autocomplete="off"
          placeholder="First Name">

      <input
          type="text" autocomplete="off"
          placeholder="Last Name">

  </div>

  <div class="input-icon">

      <i class="ri-mail-line icon"></i>

      <input
          type="email" autocomplete="off"
          placeholder="Email Address">

  </div>

  <div class="input-icon">

      <i class="ri-lock-2-line icon"></i>

      <input
          type="password" autocomplete="off"
          placeholder="Password">

      <i class="ri-eye-off-line eye"></i>

  </div>

  <div class="input-icon">

      <i class="ri-lock-password-line icon"></i>

      <input
          type="password" autocomplete="off"
          placeholder="Confirm Password">

      <i class="ri-eye-off-line eye"></i>

  </div>

  <button class="signin-btn">
      Create Account
  </button>

</form>


<!-- ========================= -->
<!-- LOGIN FORM -->
<!-- ========================= -->

<form id="loginForm" class="hidden" autocomplete="off">

  <div class="input-icon">

      <i class="ri-mail-line icon"></i>

      <input
          type="email" autocomplete="off"
          placeholder="Email Address">

  </div>

  <div class="input-icon">

      <i class="ri-lock-2-line icon"></i>

      <input
          type="password" autocomplete="off"
          placeholder="Password">

      <i class="ri-eye-off-line eye"></i>

  </div>

  <button class="signin-btn">
      Login
  </button>

</form>

    <div class="or-divider">

      <span></span>
  
      <p>OR</p>
  
      <span></span>
  
  </div>
  <div class="social-row">
    <div class="social-btn" aria-label="Sign in with Google">
      <svg viewBox="0 0 48 48"><path fill="#FFC107" d="M43.6 20.5H42V20H24v8h11.3C33.7 32.9 29.3 36 24 36c-6.6 0-12-5.4-12-12s5.4-12 12-12c3.1 0 5.9 1.2 8 3.1l5.7-5.7C34.6 6.1 29.6 4 24 4 12.9 4 4 12.9 4 24s8.9 20 20 20 20-8.9 20-20c0-1.3-.1-2.7-.4-3.5z"/><path fill="#FF3D00" d="M6.3 14.7l6.6 4.8C14.6 15.9 18.9 13 24 13c3.1 0 5.9 1.2 8 3.1l5.7-5.7C34.6 6.1 29.6 4 24 4c-7.6 0-14.1 4.3-17.7 10.7z"/><path fill="#4CAF50" d="M24 44c5.5 0 10.4-1.9 14.2-5.1l-6.6-5.4C29.6 35.4 26.9 36 24 36c-5.3 0-9.7-3.1-11.3-7.5l-6.5 5C9.8 39.6 16.4 44 24 44z"/><path fill="#1976D2" d="M43.6 20.5H42V20H24v8h11.3c-.8 2.3-2.3 4.3-4.2 5.5l6.6 5.4C41.4 35.9 44 30.5 44 24c0-1.3-.1-2.7-.4-3.5z"/></svg>
    </div>
    <div class="social-btn" aria-label="Sign in with Facebook">
      <svg viewBox="0 0 24 24"><path fill="#1877F2" d="M24 12.07C24 5.4 18.6 0 12 0S0 5.4 0 12.07C0 18.1 4.39 23.1 10.13 24v-8.44H7.08v-3.49h3.05V9.41c0-3.02 1.79-4.7 4.53-4.7 1.31 0 2.68.24 2.68.24v2.97h-1.51c-1.49 0-1.95.93-1.95 1.89v2.26h3.32l-.53 3.49h-2.79V24C19.61 23.1 24 18.1 24 12.07z"/></svg>
    </div>
    <div class="social-btn" aria-label="Sign in with Apple">
      <svg viewBox="0 0 24 24" fill="#ffffff"><path d="M16.365 1.43c0 1.14-.462 2.147-1.144 2.883-.727.79-1.923 1.396-2.94 1.318-.132-1.108.462-2.28 1.116-2.99.744-.822 2.033-1.417 2.968-1.211zm3.68 16.62c-.502 1.16-.744 1.68-1.394 2.71-.907 1.44-2.185 3.23-3.77 3.246-1.41.015-1.774-.914-3.688-.904-1.914.01-2.316.923-3.726.908-1.585-.016-2.795-1.633-3.702-3.073C1.06 17.98.15 13.85 1.42 10.94c.868-1.99 2.44-3.24 4.14-3.264 1.485-.024 2.887.998 3.688.998.8 0 2.474-1.235 4.17-1.054.71.03 2.705.287 3.987 2.16-.103.064-2.38 1.39-2.356 4.15.028 3.294 2.89 4.393 2.92 4.407z"/></svg>
    </div>
  </div>

    </div>
  </div>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.13.0/gsap.min.js"></script>
<script>

  function randChar(){
    const chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789•⌘$#@%&";
    return chars[Math.floor(Math.random()*chars.length)];
  }
  function fillNoise(el, rows, cols){
    let out = "";
    for(let r=0;r<rows;r++){
      let line = "";
      for(let c=0;c<cols;c++){
        line += Math.random() > 0.55 ? randChar() : " ";
        line += " ";
      }
      out += line + "\n";
    }
    el.textContent = out;
  }
  const rows = Math.ceil(window.innerHeight / 20);
const cols = Math.ceil(window.innerWidth / 12);

fillNoise(
    document.getElementById("noise"),
    rows,
    cols
);
const signupTab = document.getElementById("signupTab");
const loginTab = document.getElementById("loginTab");

const title = document.getElementById("title");

const signupForm = document.getElementById("signupForm");
const loginForm = document.getElementById("loginForm");


// ======================
// Show Sign Up
// ======================

function showSignup(){

    signupTab.classList.add("active");
    loginTab.classList.remove("active");

    title.textContent = "Create Account";

    gsap.timeline()

    .to(loginForm,{

        opacity:0,
        y:-15,
        duration:.18,
        ease:"power2.in"

    })

    .set(loginForm,{

        display:"none"

    })

    .set(signupForm,{

        display:"flex",
        opacity:0,
        y:15

    })

    .to(signupForm,{

        opacity:1,
        y:0,
        duration:.35,
        ease:"power2.out"

    });

}


// ======================
// Show Login
// ======================

function showLogin(){

    loginTab.classList.add("active");
    signupTab.classList.remove("active");

    title.textContent = "Welcome Back";

    gsap.timeline()

    .to(signupForm,{

        opacity:0,
        y:-15,
        duration:.18,
        ease:"power2.in"

    })

    .set(signupForm,{

        display:"none"

    })

    .set(loginForm,{

        display:"flex",
        opacity:0,
        y:15

    })

    .to(loginForm,{

        opacity:1,
        y:0,
        duration:.35,
        ease:"power2.out"

    });

}


// ======================
// Events
// ======================

signupTab.addEventListener("click",showSignup);

loginTab.addEventListener("click",showLogin);


</script>

</body>
</html>
