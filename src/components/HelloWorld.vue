<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1 style = "color:blue; text-align:center">WORLD OF WORK SERVICES - COOP</h1>
    <h2>Working with employment opportunities in:</h2>
    <h2>Sales</h2>  
    <h2>Engineering (all disciplines)</h2>
    <h2>Management (all categories)</h2>
    <h2>Construction Management</h2>
    <h2>Entry level employment</h2>
    <h2>Merit advancement</h2>
    <h2>Professional positions based upon experience and education</h2>
    <h2>Self-employment by becoming a working COOP member</h2>
    <h3>CALL (520) 300-6340<br>nk@World-of-work-services-coop.com</h3>
    <h3>Kay or Josh Harmon<br>141 S. 6th Ave, Unit 42<br>Tucson, Az 85702</h3>
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
<h3>Essential Links</h3>
    <ul>
      <li><a href="https://reference-analysis.org/work" target="_blank" rel="noopener">Misc Coding Work Menu</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
