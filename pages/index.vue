<template>
  <main>
    <form name="contact" method="POST" data-netlify="true" action="/success" data-netlify-recaptcha="true">
      <input type="hidden" name="form-name" value="contact">
      <p>
        <label>Your Name: <input type="text" name="name" /></label>
      </p>
      <p>
        <label>Your Email: <input type="email" name="email" /></label>
      </p>
      <p>
        <label>Message: <textarea name="message"></textarea></label>
      </p>
      <div data-netlify-recaptcha="true"></div>
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
