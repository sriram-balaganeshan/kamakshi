<template>
	<div >
		<v-container class="pa-6">
		<div data-aos="fade-up" data-aos-duration="700">
			<v-img width="300" class="mx-auto pa-4"  aspect-ratio="" src="/profile.jpg"></v-img>
			<h1 class="text-h2 text-center py-6 ">{{content}}</h1>
		</div>
	</v-container>
	</div>
</template>

<script type="text/javascript">

	export default{
		layout:"page",
		data(){
			return{
				content:"Content Will Be Updated here"
			}
		}
	}
</script>