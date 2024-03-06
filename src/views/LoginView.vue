<template>
  <main class="container">
    <section class="card-login">
       <header class="header-center">
          <h1>VOIP</h1>
       </header>
       <div class="body">
          <form action="" method="post" class="form">
            <div class="input-form">
              <input type="text" class="input" placeholder="Usuario" name="username">
            </div>
            <div class="input-form">
              <input type="password" class="input" placeholder="Contraseña" name="password">
            </div>
            <div class="input-form">
              <button class="btn btn-primary">okey</button>
            </div>
          </form>
       </div>
    </section>
  </main>
</template>
<style>
  .container{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .card-login{
    width: 60%;
  }
  .header-center{
    padding: 1rem;
    text-align: center;
    background-color: #3f51b5;
    color: #e8eaf6;
  }
  .body{
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.24), 0 2px 3px rgba(0, 0, 0, 0.12);
    background-color: #ffffff;
  }
  .form{
    padding: 2rem;
  }
  .input-form{
    margin-top: 1rem;
    width: 9  0%;
    /* padding: 1rem; */
  }
.input {
  width: 100%;
  height: 48px;
  padding: 12px 16px;
  font-size: 16px;
  border: none;
  border-bottom: 1px solid #ccc;
  background-color: transparent;
  transition: border-bottom-color 0.3s;
}
.input:focus {
  outline: none;
  border-bottom-color: #2196F3;
}
.input::placeholder {
  color: #999;
}
.btn {
  display: inline-block;
  padding: 12px 24px;
  font-size: 16px;
  font-weight: bold;
  text-align: center;
  text-decoration: none;
  cursor: pointer;
  border: none;
  border-radius: 4px;
  transition: background-color 0.3s;
}

.btn-primary {
  background-color: #3f8cb5;
  color: #ffffff;
}

.btn-primary:hover {
  background-color: #1976D2;
}

</style>
