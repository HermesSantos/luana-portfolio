<template >
  <div class="d-flex flex-row">
    <div class="size">
    </div>
  <div class="second text-left container">
    <div>
      <h1>
        Luana Lopes
      </h1>
    </div>
    <div>
      Marketing | Design
    </div>
    <div class="container mt-3 p-5">
      <h2>
      Sou uma designer com habilidades em marketing, que adora ajudar criativos e marcas a atrair mais atenção para o seu trabalho.
      </h2>
    </div>
  </div>
  </div>
</template>
<script>
export default {
  name: 'Main'
}
</script>
<style>
body{
  background-color: rgb(0, 29, 24);
  color: white
}
.size{
  height: 100vh;
  width: 60vw;
  background-image: url('../../public/luanac.jpeg');
  background-repeat: no-repeat;
  background-size: 80vw;
  background-position: -10vw ;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white
}
.second{
  width: 40vw;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
h1 {
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: .15em solid orange; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: .15em; /* Adjust as needed */
  animation: 
    typing 1.0s steps(40, end),
    blink-caret .50s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: orange; }
}
</style>
