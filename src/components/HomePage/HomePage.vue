<template>
  <div class="home-page">
    <div class="page-content">
      <PageInfo title="Welcome To Destiny Tools" body="Below is a range of various tools to assist players in Destiny 2 (More to come)"/>
      <ul>
        <li>
          <router-link to="StatScore">Stat Score Calculator</router-link>
        </li>
      </ul>
    </div>

  </div>
</template>

<script>
import PageInfo from '../shared/pageInfo';
export default {



  name: 'HomePage',
  components: {
    PageInfo
  }
}
</script>
