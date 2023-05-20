<script setup lang="ts">

</script>
<template>
  <footer class="footer">
    <div class="contacts">
      <h3>Contacts</h3>
      <ul>
        <li>Email: example@example.com</li>
        <li>Phone: 123-456-7890</li>
        <li>Address: 123 Street, City, Country</li>
      </ul>
    </div>
    <div class="social-media">
      <h3>Social Media</h3>
      <ul>
        <li><a href="https://www.facebook.com">Facebook</a></li>
        <li><a href="https://www.twitter.com">Twitter</a></li>
        <li><a href="https://www.instagram.com">Instagram</a></li>
      </ul>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background-color: #000000;
  color: #fafafa;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
}

.contacts,
.social-media {
  flex: 1;
  text-align: center;
}

.contacts h3,
.social-media h3 {
  margin-top: 0;
  text-align: center;
}

ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

ul li {
  margin-bottom: 10px;
}

ul li a {
  text-decoration: none;
}
</style>