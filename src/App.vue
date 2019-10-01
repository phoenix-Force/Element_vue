<template>
<div container>
<el-col :span= "8">
  <el-row class= "form-header">
    <h2>SignUp</h2>
  </el-row>
  <el-form ref="form" label-width="120px">
      <el-form-item label="First name">
        <el-input placeholder="First Name"></el-input>
      </el-form-item>
  </el-form>
  <el-form ref="form" label-width="120px">
      <el-form-item label="Last name">
        <el-input placeholder="Last Name"></el-input>
      </el-form-item>
  </el-form>
  <el-form ref="form" label-width="120px">
      <el-form-item label="Date Of birth">
        <el-date-picker

        type="date"
        placeholder="Date of Birth">

      </el-date-picker>
 <el-input placeholder="name"></el-input>
      </el-form-item>
  </el-form>
  <el-form ref="form" label-width="120px">
      <el-form-item label="Activity name">
        <el-input placeholder="name"></el-input>
      </el-form-item>
  </el-form>
  <el-form ref="form" label-width="120px">
      <el-form-item label="Activity name">
        <el-input placeholder="name"></el-input>
      </el-form-item>
  </el-form>
</el-col>
</div>


</template>



<script>
export default {

}
</script>

<style scoped>
.form-header{
  text-align: center;
  color:#42193B;
  font-size: 20px;
}

</style>
