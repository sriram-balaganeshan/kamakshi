<template>
	<div data-aos="fade-up" data-aos-duration="700">
		<v-container >
			<h1 class="text-h3 text-center">Gallery</h1>
			<v-row>
				<v-col cols="12" md="3">
					<v-hover>
						<template v-slot:default="{ hover }">
							<v-card link to="/gallery/photos#section1" class="mx-auto" >
							<v-img src="/data/kanchi_kamakshi_temple.jpg" aspect-ratio="1.5"></v-img>

							<v-card-text>
								<h2 class="title primary--text text-center">
									Temple Photos
								</h2>
							</v-card-text>
							<v-fade-transition>
								<v-overlay
								v-if="hover"
								absolute
								color="#036358"
								>
								<v-btn text link to="/gallery/photos#section1" >View More</v-btn>
							</v-overlay>
						</v-fade-transition>
					</v-card>
				</template>
			</v-hover>
		</v-col>

					<v-col cols="12" md="3">
					<v-hover>
						<template v-slot:default="{ hover }">
							<v-card link to="/gallery/photos#section1" class="mx-auto" >
							<v-img src="/data/festival.jpg" aspect-ratio="1.5"></v-img>

							<v-card-text>
								<h2 class="title primary--text text-center">
										Festival Photos
								</h2>
							</v-card-text>
							<v-fade-transition>
								<v-overlay
								v-if="hover"
								absolute
								color="#036358"
								>
								<v-btn text link to="gallery/photos#section1">View More</v-btn>
							</v-overlay>
						</v-fade-transition>
					</v-card>
				</template>
			</v-hover>
		</v-col>

					<v-col cols="12" md="3">
					<v-hover>
						<template v-slot:default="{ hover }">
							<v-card link to="/gallery/photos#section1" class="mx-auto" >
							<v-img src="/data/pooja.jpg" aspect-ratio="1.5"></v-img>

							<v-card-text>
								<h2 class="title primary--text text-center">
									Pooja Photos
								</h2>
							</v-card-text>
							<v-fade-transition>
								<v-overlay
								v-if="hover"
								absolute
								color="#036358"
								>
								<v-btn link text to="gallery/photos#section1">View More</v-btn>
							</v-overlay>
						</v-fade-transition>
					</v-card>
				</template>
			</v-hover>
		</v-col>

					<v-col cols="12" md="3">
					<v-hover>
						<template v-slot:default="{ hover }">
							<v-card link to="/gallery/photos#section1" class="mx-auto" >
							<v-img src="/data/goddes.jpg" aspect-ratio="1.5"></v-img>

							<v-card-text>
								<h2 class="title primary--text text-center">
									Goddess Photos
								</h2>
							</v-card-text>
							<v-fade-transition>
								<v-overlay
								v-if="hover"
								absolute
								color="#036358"
								>
								<v-btn link text to="gallery/photos#section1">View More</v-btn>
							</v-overlay>
						</v-fade-transition>
					</v-card>
				</template>
			</v-hover>
		</v-col>




	</v-row>

</v-container>
</div>
</template>

<script type="text/javascript">
	export default{
		data(){
			return{

			}
		}
	}
</script>

<style lang="css" scoped>
</style>