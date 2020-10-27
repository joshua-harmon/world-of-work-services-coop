<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <h1 style = "color:blue; text-align:center">WORLD OF WORK SERVICES COOP</h1>
    <h2>sales</h2>
    <h2>construction management and all engineering</h2>
    <h2>entry level</h2>
    <h2>merit advancement</h2>
    <h2>professional positions based upon experience and education</h2>
    <h2>self-employment can immediately become part of the coop and can make money</h2>
    <h2>employment-work options</h2>
<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" size="50" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" size="50" /></label>
  </p>
  <p>
    <label>Your Role: <select name="role[]" multiple>
      <option value="entry-level">entry level</option>
      <option value="sales">sales</option>
      <option value="software">software</option>
      <option value="hardware">hardware</option>
      <option value="manufacturing">manufacturing</option>
      <option value="construction">construction</option>
      <option value="other">other</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message" rows="8" columns=10></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

