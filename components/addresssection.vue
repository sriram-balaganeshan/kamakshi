<template>
	<div data-aos="fade-in" data-aos-duration="1000">
		<v-container class="pa-3">
			<h1 class="text--h3 text-center">Address</h1>
			<v-row>
				<v-col cols="12" md="6" class="text-center">
					<p class="text-h4">Sri Kanchi Kamakshi Ambal Devasthanam</p>
					<p class="mb-0 text-h6">New No. 6, Old No. 144/A</p>
					<p class="mb-0 text-h6">Kamakshi Amman Street</p>
					<p class="mb-0 text-h6">Big Kanchipuram - 631502</p>
					<p class="mb-0 text-h6">Tamilnadu</p>
					<p class="mb-0 text-h6">syamasastri@gmail.com</p>
				</v-col>

				<v-col cols="12" md="6">
					<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15560.159923981824!2d79.703183!3d12.840693!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xeb0a104aa53ed53!2sSri%20Kanchi%20Kamakshi%20Amma%20Temple!5e0!3m2!1sen!2sin!4v1602819629812!5m2!1sen!2sin" width="100%" height="100%" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
				</v-col>
			</v-row>
		</v-container>
	</div>
</template>

<script type="text/javascript">
	export default{
		name:"addresssection",
		data(){
			return{
				"text":"Hello"
			}
		}
	}
</script>

<style lang="css" scoped>
	p{
		margin-bottom: 1px;
	}
</style>