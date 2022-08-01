<template>
  <main>
    <form name="form-name" value="contact" method="POST" data-netlify="true" action="/success" netlify-honeypot="bot-field">
      <p class="hidden">
       <input type="hidden" name="bot-field" />
      </p>
      <input type="hidden" name="form-name" value="contact">
      <p>
        <label>Your Name: <input type="text" name="name" required/></label>
      </p>
      <p>
        <label>Your Email: <input type="email" name="email" required/></label>
      </p>
      <p>
        <label>Message: <textarea name="message" required></textarea></label>
      </p>
      <p>
        <button type="submit">Send</button>
      </p>
    </form>
  </main>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
