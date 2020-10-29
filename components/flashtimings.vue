<template>
	<div>
		<v-row dense class="pt-2">
			<v-col cols="12" md="12">
				<marquee width="100%" direction="right">
				<v-chip color="pink" label  class="mr-4" text-color="white">
					<v-icon left>mdi-label</v-icon>Timings: Morning 5.30-11.30
				</v-chip>

				<v-chip color="green" label   class="mr-4" text-color="white">
					<v-icon left>mdi-label</v-icon>Timings: Evening 4.30-8.30
				</v-chip>

<!-- 				<v-chip color="orange" class="mr-4" label text-color="white">
					<v-icon left>mdi-flag</v-icon>Food Break 12 PM
				</v-chip>

				<v-chip color="blue" label  class="mr-4" text-color="white">
					<v-icon left>mdi-label</v-icon>Closing Time: 10 PM
				</v-chip> -->
			</marquee>

		</v-col>
	</v-row>
</div>
</template>

<script type="text/javascript">
	export default{
		methods:{
			opennav:function () {
				console.log("TRRIG")
			}
		}
	}
</script>