<template>
	<section>
        <div class="container" style="padding-top:80px; padding-bottom:550px; text-align: center">
            <div class="col-sm-12 col-md-12" style="">
                <div>
                    <h1>Documentation Page</h1>
                </div>
            </div>
        </div>
	</section>
</template>


<script type="text/javascript">
	export default{
		data(){
			return{
				url : this.$root.uri
			}
		},
		created(){
			this.$root.$emit('updateClass','pageDocumentation');

			//document.head.querySelector('meta[name=description]').content = 'DocumentationMeta';
		},
		mounted(){

		}
	}
</script>
