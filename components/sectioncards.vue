<template>
	<div >
		<v-row class="pa-6 pt-0">
			<v-col cols="12" md="4" v-for="i in content" :key="i.id">
				<v-card  class="mx-auto elevation-4" tile >
					<v-img
					:src="i.img"
					aspect-ratio=1.5
					></v-img>

					<v-card-title class="text-center">
						{{i.title}}
					</v-card-title>
					<p class="text-center px-3">
						{{i.content}}
					</p>


					<v-card-actions>
						<v-btn link :to="i.location" color="green darken-2" text block >
						Explore
					</v-btn>

					

				</v-card-actions>
			</v-card>
		</v-col>
	</v-row>

</div>
</template>

<script type="text/javascript">

	export default{
		name:"sectioncards",
		data(){
			return{
				content:[
				{	
					"id":1,
					"title":"About Kanchipuram - City Of Temples",
					"img":"/data/templetower2.jpg",
					"content":"Kanchipuram is one of the seven sacred cities in India. History proclaims that Kanchipuram was ruled by the Pallava Kings...",
					"location":"/about/kanchipuram"
				},
				{
					"id":2,
					"title":"About Goddess Kamakshi",
					"img":"/fsimg/n3.jpeg",
					"content":"The Goddess Kamakshi is in a sitting posture in the temple. This posture is called the Padmasana posture. The Padmasana ...",
					"location":"/about/goddess_kamakshi"
				},
				{
					"id":3,
					"title":"About Kanchi Kamakshi Temple",
					"img":"/data/templetower.jpg",
					"content":"Kanchi Kamakshi temple is situated at about 5 acres of land and has four entrances. The main entrance of the temple...",
					"location":"/about/temple"
				},
				]
			}
		}

	}
</script>

