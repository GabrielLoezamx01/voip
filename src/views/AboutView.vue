<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div class="container">
      <div class="row">
        <div class="col">
          <form action="">
            <div class="form-floating mb-3">
              <input
                type="text"
                class="form-control material"
                id="floatingInput"
                placeholder="Label"
              />
              <label for="floatingInput">Nombre de usuario</label>
            </div>
            <div class="form-floating mb-3">
              <textarea
                class="form-control material"
                placeholder="Leave a comment here"
                id="floatingTextarea"
              ></textarea>
              <label for="floatingTextarea">Comments</label>
            </div>
            <div class="select">
              <select class="select-text" required>
                <option value="" disabled selected></option>
                <option value="1">Option 1</option>
                <option value="2">Option 2</option>
                <option value="3">Option 3</option>
              </select>
              <span class="select-highlight"></span>
              <span class="select-bar"></span>
              <label class="select-label">Select</label>
            </div>
          </form>
        </div>
        <div class="col">
          <button class="btn btn-material btn-primary">Primary Button</button>
          <button class="btn btn-material btn-secondary">
            Secondary Button
          </button>
          <button class="btn btn-material btn-success">Success Button</button>
          <button class="btn btn-material btn-info">Info Button</button>
          <button class="btn btn-material btn-warning">Warning Button</button>
          <button class="btn btn-material btn-danger">Danger Button</button>
          <button class="btn btn-material btn-light">Light Button</button>
          <button class="btn btn-material btn-dark">Dark Button</button>
        </div>
        <div class="card" style="width: 18rem">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="form-check custom-checkbox">
          <input
            class="form-check-input custom-control-input"
            type="checkbox"
            value=""
            id="customCheck1"
          />
          <label
            class="form-check-label custom-control-label"
            for="customCheck1"
          >
            Check 1
          </label>
        </div>

        <!-- Radio button personalizado -->
        <div class="form-check custom-radio">
          <input
            class="form-check-input custom-control-input"
            type="radio"
            name="exampleRadio"
            id="customRadio1"
            value="option1"
          />
          <label
            class="form-check-label custom-control-label"
            for="customRadio1"
          >
            Option 1
          </label>
        </div>
        <div class="form-check custom-radio">
          <input
            class="form-check-input custom-control-input"
            type="radio"
            name="exampleRadio"
            id="customRadio2"
            value="option2"
          />
          <label
            class="form-check-label custom-control-label"
            for="customRadio2"
          >
            Option 2
          </label>
        </div>

        <!-- Formulario básico -->
        <div class="mb-3">
          <label for="exampleFormControlInput1" class="form-label"
            >Email address</label
          >
          <input
            type="email"
            class="form-control material"
            id="exampleFormControlInput1"
            placeholder="name@example.com"
          />
        </div>
        <div class="mb-3">
          <label for="exampleFormControlTextarea1" class="form-label"
            >Example textarea</label
          >
          <textarea
            class="form-control material"
            id="exampleFormControlTextarea1"
            rows="3"
          ></textarea>
        </div>
        <div>
          <input type="password" class="form-control" />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
