<template>
    <div class="demo-container">
        <ul>
            <li><router-link to="/nvbaseui">nv-baseui</router-link></li>
            <li><router-link to="/nvtable">nv-table</router-link></li>
            <li><router-link to="/nvfiltertable">nv-filtertable</router-link></li>
            <li><router-link to="/nvform">nv-form</router-link></li>
            <li><router-link to="/nvicon">nv-icon</router-link></li>
            <li><router-link to="/nvtree">nv-tree</router-link></li>
            <li><router-link to="/nvdatepicker">nv-datepicker</router-link></li>
            <li><router-link to="/nvchart">nv-chart</router-link></li>
            <li><router-link to="/nvtrend">nv-trend</router-link></li>
            <!-- <li><router-link to="/nvcontrasttrend">nv-contrasttrend</router-link></li> -->
            <li><router-link to="/nvlist">nv-list</router-link></li>
            <li><router-link to="/nvdialog">nv-dialog</router-link></li>
            <li><router-link to="/nvswitch">nv-switch</router-link></li>
            <li><router-link to="/nvbutton">nv-button</router-link></li>
            <li><router-link to="/nvtextline">nv-textline</router-link></li>
            <li><router-link to="/nvsteps">nv-steps</router-link></li>
            <li><router-link to="/nvsearch">nv-search</router-link></li>
            <li><router-link to="/nvtag">nv-tag</router-link></li>
            <li><router-link to="/nv404">nv-404</router-link></li>
        </ul>
        <router-view></router-view>
    </div>
</template>
<script>
export default {
    name: 'App',
    data () {
        return {}
    }
}
</script>
<style lang="less" >
.demo-container {
    padding: 20px 40px; 
    margin-bottom: 40px;
    ul { display: flex; flex-wrap: wrap; margin-bottom: 30px;}
    li { display: inline-block; margin-right: 20px; font-size: 14px; min-width: 90px;margin-bottom: 20px;}
    li:hover {
        text-decoration: underline;
        cursor: pointer;
    }
}

</style>
