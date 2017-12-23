<template lang="html">
  <Row type="flex" class="section" justify="center">
    <Col>
      <h1 class="title">What you can ask Alexa:</h1>
      <p class="sub-title-2">
        Ask for any <span class="data-point">Data Point</span> for any publicly traded <span class="company-name">Company</span>
      </p>
      <Row type="flex" align="middle" justify="center" style="padding: 40px;">
        <Card class="card">
          <Icon type="quote"></Icon>
          <p class="example">
            "What was the <span class="data-point">opening price</span> for <span class="company-name">Apple</span>?"
          </p>
        </Card>
        <Card class="card">
          <Icon type="quote"></Icon>
          <p class="example">
            "What was the <span class="data-point">closing price</span> for <span class="company-name">Amazon</span>?"
          </p>
        </Card>
        <Card class="card">
          <Icon type="quote"></Icon>
          <p class="example">
            "What was the <span class="data-point">last price</span> for <span class="company-name">Facebook</span>?"
          </p>
        </Card>
        <Card class="card">
          <Icon type="quote"></Icon>
          <p class="example">
            "What is the <span class="data-point">52 week low</span> for <span class="company-name">Bank of America</span>"
          </p>
        </Card>
        <Card class="card">
          <Icon type="quote"></Icon>
          <p class="example">
            "How many <span class="data-point">employees</span> does <span class="company-name">Tesla</span> have"
          </p>
        </Card>
      </Row>
    </Col>
  </Row>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
.section {
  padding: 16px;
}
.title {
    font-size: 24px;
    padding-top: 40px;
}
.sub-title-2 {
  font-size: 20px;
}
span.data-point {
  font-weight: 600;
  color: #2fc17f;
}

span.company-name {
  font-weight: 600;
  color: #15abe1;
}

.example {
  font-size: 18px;
  color: #2c3e50;
  text-align: center;
}
.card {
  width: 300px;
  margin: 8px;
}
</style>
