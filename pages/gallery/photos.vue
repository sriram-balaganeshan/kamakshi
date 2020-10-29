<template>
	<div>
	<div data-aos="slide-up" data-aos-duration="1000">
		<v-container class="pa-3" >
			<h1 class="text--h3 text-center">Temple Photos</h1>
			<v-row wrap>
				<v-col  cols="6" md="3">
					<v-img src="/data/kanchi_kamakshi_temple.jpg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col  cols="6" md="3">
					<v-img src="/data/templetower.jpg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col  cols="6" md="3">
					<v-img src="/data/templetower2.jpg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col  cols="6" md="3">
					<v-img src="/data/kanchipuram.jpg" aspect-ratio="1.5"></v-img>
				</v-col>
			</v-row>
		</v-container>

		<v-container class="pa-3">
			<h1 class="text--h2 text-center" >Festival Photos</h1>
			<v-row wrap>

				<v-col cols="6" md="3" >
					<v-img lazy-src src="/data/festival.jpg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/data/pooja.jpg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/data/festival2.jpg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/data/festival3.jpg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/fsimg/n1.jpeg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/fsimg/n2.jpeg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/fsimg/n3.jpeg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/fsimg/n4.jpeg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/fsimg/n5.jpeg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/fsimg/n6.jpeg" aspect-ratio="1.5"></v-img>
				</v-col>
				<v-col cols="6" md="3" >
					<v-img lazy-src src="/fsimg/n7.jpeg" aspect-ratio="1.5"></v-img>
				</v-col><v-col cols="6" md="3" >
					<v-img lazy-src src="/fsimg/n8.jpeg" aspect-ratio="1.5"></v-img>
				</v-col>
			</v-row>
		</v-container>

		<v-container class="pa-3">
			<h1 class="text--h2 text-center">Goddes Photos</h1>
			<v-row wrap>

				<v-col cols="6" md="3">
					<v-img lazy-src src="/fsimg/n7.jpeg"  aspect-ratio="1.5" ></v-img>
				</v-col>

				<v-col cols="6" md="3">
					<v-img lazy-src src="/data/goddes.jpg" aspect-ratio="1.5" ></v-img>
				</v-col>

				<v-col cols="6" md="3">
					<v-img lazy-src src="/data/kamakshi.jpg" aspect-ratio="1.5" ></v-img>
				</v-col>

				<v-col cols="6" md="3">
					<v-img lazy-src src="/data/goddes1.jpg" aspect-ratio="1.5"></v-img>
				</v-col>
			</v-row>
		</v-container>
			</div>
	</div>
</template>

<script type="text/javascript">
	export default{
		layout:"page",
		data(){
			return{
				section1:[
				{
					"id":1,
					"img":"https://wiredstore.now.sh/img1.jpeg"
				},
				{
					"id":1,
					"img":"https://wiredstore.now.sh/img1.jpeg"
				},
				{
					"id":1,
					"img":"https://wiredstore.now.sh/img1.jpeg"
				},
				{
					"id":1,
					"img":"https://wiredstore.now.sh/img1.jpeg"
				},
				]
			}
		}
	}
</script>