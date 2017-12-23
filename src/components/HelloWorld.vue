<template>
  <div class="">

    <Affix>
      <Row type="flex" align="middle" justify="space-around" class="background-dark">
        <Col span="12">
          <h1 style="font-size: 20px;">Market Savvy Alexa Skill</h1>
        </Col>
        <Col span="12">
          <div class="cta">
            <a href="https://www.amazon.com/dp/B01N4OW2Z4/ref=syps" target="_blank">
              <Button type="primary" style="background: #35d68d; border-color: #35d68d">Get the Alexa Skill</Button>
            </a>
          </div>
        </Col>
      </Row>
    </Affix>

    <Examples></Examples>
    <DataPoints></DataPoints>
  </div>
</template>

<script>
import Examples from './Examples'
import DataPoints from './DataPoints'

export default {
  name: 'HelloWorld',
  data () {
    return { alexaSkillLink: 'https://www.amazon.com/dp/B01N4OW2Z4/ref=syps' }
  },
  components: { Examples, DataPoints }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p.sub-header {
  font-size: 16px;
}
.cta {
  margin: 16px 16px;
  font-weight: 600;
}
.background-dark {
  background: rgba(0, 0, 0, 0.8);
  color: #fff;
}
</style>
