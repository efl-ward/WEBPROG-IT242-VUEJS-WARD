<template>
  <div class="personal-web">
    <header class="py-4 text-center">
      <h1 class="fw-bold">Ward's Profile</h1>
      <p class="text-muted">
        Eduard Florence L. Serna | Information Technology Student
      </p>
    </header>

    <main class="container my-5">
      <section class="row align-items-center">
        <div class="col-md-4 text-center mb-4">
          <img
            class="profile-img"
            src="https://raw.githubusercontent.com/efl-ward/mobprog_finals/refs/heads/main/kendrick%20lmao.jpg"
            alt="Profile"
          />
        </div>

        <div class="col-md-8">
          <h3>About Me</h3>
          <p>
            I am an Information Technology student passionate about web
            development and software engineering.
          </p>
        </div>
      </section>
    </main>

    <footer class="text-center py-3">
      <small>© 2026 Ward's Profile</small>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'PersonalWeb'
}
</script>

<style scoped>
body {
  background: #fff;
  color: #000;
}

header {
  border-bottom: 2px solid #000;
}

section {
  margin-top: 3rem;
}

.profile-img {
  width: 200px;
  height: 200px;
  object-fit: cover;
  border-radius: 50%;
  border: 2px solid #000;
}

footer {
  border-top: 1px solid #000;
  margin-top: 4rem;
}
</style>