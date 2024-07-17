<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import IconTruck from "@/components/icons/IconTruck.vue";
import IconDriver from "@/components/icons/IconDriver.vue";
import IconMap from "@/components/icons/IconMap.vue";
import IconHandShake from "@/components/icons/IconHandShake.vue";
import IconComments from "@/components/icons/IconComments.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <IconTruck/>
    </template>
    <template #heading>Fleet</template>
    Our fleet of well-serviced box trucks is designed for reliable and efficient delivery. Regularly maintained and
    equipped with the latest technology, our trucks ensure your goods are transported safely and on time.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconDriver/>
    </template>
    <template #heading>Drivers</template>
    Our professional drivers are the backbone of our reliable transportation services. Experienced, skilled, and
    dedicated to safety, they ensure your goods are delivered on time and in perfect condition.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconMap/>
    </template>
    <template #heading>Geography</template>
    delivers across the USA and Canada, covering urban centers and remote areas alike. Our robust logistics network
    ensures reliable transportation for your goods, wherever you need them to go.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconHandShake/>
    </template>
    <template #heading>Career</template>
    Join a dynamic team dedicated to delivering excellence in transportation and logistics. Take the next step in your
    career with us and contribute to our success in the transportation
    industry.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconComments/>
    </template>
    <template #heading>Contacts</template>
    We're here to assist you with any inquiries about our transportation services. Whether you're a prospective client,
    a job seeker, or have general questions, reach out to us via phone or email.

    <br>
    <br>

    Call us: <a class="underline font-bold" href="tel:+14407091601">+1 (440) 709-1601</a>
    <br>
    Text us: <a class="underline font-bold" href="mailto:firstclassdeliveryllc2023@gmail.com">teo.partizan@gmail.com</a>

  </WelcomeItem>
</template>
