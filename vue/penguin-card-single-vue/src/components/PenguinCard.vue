<template>
  <div>
    <div class="component-penguin-card">
      <img
        src="/playground_assets/rectangle1279-3ppgu-400h.png"
        alt="Rectangle1279"
        class="component-rectangle1"
      />
      <img
        src="/playground_assets/image2280-ged3-200h.png"
        alt="image2280"
        class="component-image2"
      />
      <img
        src="/playground_assets/ellipse1281-8lw-200h.png"
        alt="Ellipse1281"
        class="component-ellipse1"
      />
      <img
        src="/playground_assets/vector282-b7a.svg"
        alt="Vector282"
        class="component-vector"
      />
      <img
        src="/playground_assets/rectangle2283-yuci-200h.png"
        alt="Rectangle2283"
        class="component-rectangle2"
      />
      <span class="component-text"><span>TOPIC</span></span>
      <span class="component-text2">
        <span>
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry&apos;s standard dummy
          text.
        </span>
      </span>
      <span class="component-text4">
        <span>Lorem Ipsum is simply dummy</span>
      </span>
      <span class="component-text6"><span>by Philip Jun 15</span></span>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'PenguinCard',
    props: {},
  };
</script>

<style scoped>
  .component-penguin-card {
    width: 300px;
    height: 400px;
    display: flex;
    overflow: hidden;
    position: relative;
    max-width: 300px;
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
    box-sizing: border-box;
    align-items: flex-start;
    flex-shrink: 0;
    border-color: transparent;
    border-radius: 10px;
  }
  .component-rectangle1 {
    top: 0px;
    left: 0px;
    width: 300px;
    height: 400px;
    position: absolute;
    box-sizing: border-box;
    border-color: transparent;
    margin-right: 0;
    border-radius: 10px;
    margin-bottom: 0;
  }
  .component-image2 {
    top: 0px;
    left: 0px;
    width: 300px;
    height: 191px;
    position: absolute;
    box-sizing: border-box;
    border-color: transparent;
    margin-right: 0;
    border-radius: 10px 10px 0 0;
    margin-bottom: 0;
  }
  .component-ellipse1 {
    top: 169px;
    left: 248px;
    width: 45px;
    height: 45px;
    position: absolute;
    box-sizing: border-box;
    border-color: transparent;
    margin-right: 0;
    margin-bottom: 0;
  }
  .component-vector {
    top: 184px;
    left: 261px;
    width: 20px;
    height: 15px;
    position: absolute;
    box-sizing: border-box;
    margin-right: 0;
    margin-bottom: 0;
  }
  .component-rectangle2 {
    top: 225px;
    left: 13px;
    width: 274px;
    height: 154px;
    position: absolute;
    box-sizing: border-box;
    border-color: transparent;
    margin-right: 0;
    border-radius: 10px;
    margin-bottom: 0;
  }
  .component-text {
    top: 225px;
    left: 24px;
    color: rgba(55, 54, 54, 1);
    width: 61px;
    height: auto;
    position: absolute;
    font-size: 15px;
    align-self: auto;
    font-style: Regular;
    text-align: left;
    font-family: Noto Sans;
    font-weight: 400;
    line-height: 20px;
    font-stretch: normal;
    margin-right: 0;
    margin-bottom: 0;
    text-decoration: none;
  }
  .component-text2 {
    top: 285px;
    left: 26px;
    color: rgba(73, 72, 72, 1);
    width: 255px;
    height: auto;
    position: absolute;
    font-size: 11px;
    align-self: auto;
    font-style: Display Light;
    text-align: left;
    font-family: Noto Sans;
    font-weight: 300;
    line-height: 20px;
    font-stretch: normal;
    margin-right: 0;
    margin-bottom: 0;
    text-decoration: none;
  }
  .component-text4 {
    top: 256px;
    left: 26px;
    color: rgba(0, 0, 0, 1);
    height: auto;
    position: absolute;
    font-size: 16px;
    align-self: auto;
    font-style: Display Bold;
    text-align: left;
    font-family: Noto Sans;
    font-weight: 700;
    line-height: 20px;
    font-stretch: normal;
    margin-right: 0;
    margin-bottom: 0;
    text-decoration: none;
  }
  .component-text6 {
    top: 353px;
    left: 26px;
    color: rgba(73, 72, 72, 1);
    height: auto;
    position: absolute;
    font-size: 10px;
    align-self: auto;
    font-style: Display Light;
    text-align: left;
    font-family: Noto Sans;
    font-weight: 300;
    line-height: 20px;
    font-stretch: normal;
    margin-right: 0;
    margin-bottom: 0;
    text-decoration: none;
  }
</style>
