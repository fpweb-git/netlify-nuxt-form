<template>
  <main>
    <form name="contact" method="POST" data-netlify="true" action="/success" netlify-honeypot="bot-field">
      <input type="hidden" name="bot-field" />
      <input type="hidden" name="form-name" value="contact">
      <input type="hidden" name="subject" value="Vous avez reçu un nouveau message" />
      <div>
        <label for="name">Your Name:</label>
        <input type="text" name="name" required/>
      </div>
      <div>
        <label for="email">Your Email:</label>
        <input type="email" name="email" required/>
      </div>
      <div>
        <label for="message">Message:</label>
        <textarea name="message" required></textarea>
      </div>
      <div>
        <label for="Accepté">J'accepte</label>
        <input type="checkbox" name="Accepté" required/>
      </div>
      <div>
        <button type="submit">Send</button>
      </div>
    </form>
  </main>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
