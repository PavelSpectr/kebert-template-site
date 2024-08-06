<script>
export default {
  data() {

  }
}
</script>

<template>
  <header v-show="true">
    <span>"Официальный сайт адвоката Кеберт Нины Юрьевны"</span>
    <nav>
      <ul>
        <li>
          <a href="#about">About</a>
        </li>
        <li>
          <a href="#contacts">Contacts</a>
        </li>
        <li>
          <a href="#events">Events</a>
        </li>
        <li>
          <a href="#docs">Documents</a>
        </li>
        <li>
          <a href="#panel">Panel</a>
        </li>
      </ul>
    </nav>
  </header>
  <hr/>
  <main>
    <h1>
      "Официальный сайт адвоката Кеберт Нины Юрьевны"
    </h1>
    <section>
      <img src="./assets/img1.jpg" width="10%"/>
      <img src="./assets/img2svg.svg" width="10%"/>
    </section>
    <section id="about">
      <h2>"Обо мне"</h2>
      <p>"Я самый <em>крутейший адвокат</em> во вселенной. Люблю <strong>ходить в горы</strong>."</p>
    </section>
    <section id="contacts">
      <h2>"Контакты"</h2>
      <address>
        "г.Иркутск, ул. Трилиссера, 87, офис 306"
      </address>
    </section>
    <section id="events">
      <h2>"События"</h2>
      <p>"Сначала оплата, потом события"</p>
    </section>
    <section id="documents">
      <h2>"Документы"</h2>
      <p>"Дохуя документов"</p>
    </section>
  </main>
  <footer>
    <section id="panel">
      <div class="panel-button">
        <a href="tel:+79021718494"><img src="./assets/call.svg"  alt="Call" target="_blank"/></a>
      </div>
      <div class="panel-button">
        <a href="https://t.me/kebert_n"><img src="./assets/message.svg"  alt="Send Message" target="_blank" /></a>
      </div>
    </section>
  </footer>
</template>

<style scoped>

</style>
