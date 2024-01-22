# mock-api-template
 const url = "https://mock-api-template-j6kc.onrender.com/register";
      const baseurl = `https://mock-api-template-j6kc.onrender.com/`;
      const pass_field = document.querySelector(".pass-key");
      const showBtn = document.querySelector(".show");
      showBtn.addEventListener("click", function () {
        if (pass_field.type === "password") {
          pass_field.type = "text";
          showBtn.textContent = "HIDE";
          showBtn.style.color = "#3498db";
        } else {
          pass_field.type = "password";
          showBtn.textContent = "SHOW";
          showBtn.style.color = "#222";
        }
      });
      let submit_btn = document.getElementById("submit-btn");
      submit_btn.addEventListener("submit",handleLogin);
      async function handleLogin(e) {
          alert("working")
      } const url = "https://mock-api-template-j6kc.onrender.com/register";
      const baseurl = `https://mock-api-template-j6kc.onrender.com/`;
      const pass_field = document.querySelector(".pass-key");
      const showBtn = document.querySelector(".show");
      showBtn.addEventListener("click", function () {
        if (pass_field.type === "password") {
          pass_field.type = "text";
          showBtn.textContent = "HIDE";
          showBtn.style.color = "#3498db";
        } else {
          pass_field.type = "password";
          showBtn.textContent = "SHOW";
          showBtn.style.color = "#222";
        }
      });
      let submit_btn = document.getElementById("submit-btn");
      submit_btn.addEventListener("submit",handleLogin);
      async function handleLogin(e) {
          alert("working")
      }