<template>
	<div>
		<v-carousel
		cycle
		hide-delimiter-background
		hide-delimiters	
		show-arrows-on-hover
		height="440"
		class="hidden-sm-and-down"
		>
		<v-carousel-item
		v-for="(slide, i) in slides"
		:key="i"
		:src="slide.src">

<!-- 		<v-row class="fill-height" align="center" justify="center">
			<div class="display-3 font-weight-black pa-3 text-center" style="text-shadow: 1px 1px 20px black" >
				
			</div>
		</v-row> -->

	</v-carousel-item>
</v-carousel>

	<v-carousel
		cycle
		hide-delimiter-background
		hide-delimiters	
		show-arrows-on-hover
		height="440"
		class="hidden-sm-and-up"
		>
		<v-carousel-item
		v-for="(slide, i) in slides2"
		:key="i"
		:src="slide.src">

<!-- 		<v-row class="fill-height" align="center" justify="center">
			<div class="display-3 font-weight-black pa-3 text-center" style="text-shadow: 1px 1px 20px black" >
				
			</div>
		</v-row> -->

	</v-carousel-item>
</v-carousel>
</div>
</template>

<script>
	export default{
		data(){
			return{
				slides:[
				{
					'src':'/indeximg/banner2a.jpg'
				},
				{
					'src':'/indeximg/bannerwall1.jpg'
				},
				
				{
					'src':'/indeximg/banner2s.jpeg'
				},
				],
				slides2:[
				{
					'src':'/data/br1.jpeg'
				},
				{
					'src':'/indeximg/bannerwall1.jpg'
				},
				{
					'src':'/indeximg/mbanner1.jpg'
				},
				]
			}
		},

	}
</script>