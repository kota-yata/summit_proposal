<template>
  <section class="about-us" id="about-us">
    <div class="about-us-container container">
      <h2 class="main-title drark">什麼是 g0v？</h2>
      <div class="content">
        <p>
          自 2012 年以來，公民科技運動風起雲湧。以開放透明、公民參與為號召的
          <a href="https://g0v.tw/zh-TW/">g0v 台灣零時政府</a
          >社群在同年底號召了第一場活動，以「寫程式改造社會」為口號，從此公民科技之火開始延燒，至今未歇。
        </p>
        <p>
          八年間，在上千位參與者集體的貢獻下，透過一場場黑客松，打造出多項以開放資料、開放政府為精神的資訊平台，以縮短數位落差為初衷，降低公民參與門檻，使得議題審議可立基在具體事實，也提升理性討論公共事務的意識。
        </p>
        <p>
          在這場開放資料、開放政府的運動中，g0v
          社群也開創出台灣公民社會與政府互動的新模式。
        </p>
        <p>
          Since 2012, the civic tech movement has been sweeping across the
          globe. g0v, a community that advocates open source, transparency of
          information and civic participation, also rode the wave and launched
          the first event that year with the slogan ““Code to refactor
          society””. Since then, the movement continues with no sight of ending.
        </p>
        <p>
          Over the past 8 years, g0v has invited thousands of participants to
          join our hackathons and in turn created several platforms that promote
          open data and open government. g0v aims to reduce the digital divide
          and allow citizens easy access to public information, so that
          discussion of issues can be based on facts. It can also raise the
          awareness of rational discussion on public affairs.
        </p>
        <p>
          With its emphasis on openness and participation, g0v community has
          created a new model for the Taiwan society and the government to
          interact with each other in this open data and open government
          movement.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AboutUS"
};
</script>

<style lang="scss" scoped>
.about-us {
  background-image: url("../../assets/images/activity.jpg");
  background-size: contain;
  background-attachment: fixed;
}
.about-us-container {
  padding-top: 45px;
  padding-bottom: 45px;
  h2 {
    margin-bottom: 50px;
  }
  .content {
    padding: 30px;
    background-color: #ffffffa8;
    border-radius: 4px;
  }
  p {
    color: #000;
    font-size: 17px;
    margin-bottom: 25px;
    font-weight: 500;
  }
  p:last-child {
    margin-bottom: 0;
  }
}
</style>
