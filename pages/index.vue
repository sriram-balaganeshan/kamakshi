<template>
	<div >

		<topbar />
		<headslider />
		<navbar class="hidden-sm-and-down" v-intersect="onIntersect1"
		 :class="{sticknav : isIntersecting1 }"  /> 
		<navdialog class="hidden-md-and-up"/>
		<flashtimings />
		<sectioncards />
		<videosection/>
		<vissionsection />
		<events />
		<indexgallery />
		<addresssection />
		<footersection />
	</div>
</template>

<script>
	export default{
		data(){
			return{
				isIntersecting1: false,
			}
		},
		methods:{
			onIntersect1 (entries, observer) {
			this.isIntersecting1 = true
			// this.isIntersecting = entries[0].isIntersecting
   		},
   		opennav(e){
   			console.log('TRR')
   		}
	},
	mounted(){
		this.isIntersecting1 = false
	}
}
</script>

<style type="text/css">

@media only screen and (min-width: 768px){
	.sticknav{
		position: sticky;
		width: 100%;
		top: 0px;
		z-index: 100;
	}
}

</style>