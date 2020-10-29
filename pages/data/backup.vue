<template>
	<div>
		<navbar/>
	
	<div data-aos="fade-down" data-aos-duration="700" >
		<div data-aos="fade-in" data-aos-duration="700">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">About Goddess Kamakshi</h1>
				<v-divider></v-divider>
				<v-row wrap>		
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>

					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>
				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section2">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Temple Legend</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>		
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>				
				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section3">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">History</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>		

				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section4">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">About Kanchi</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>	
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section5">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Other Temple</h1>
				<v-divider></v-divider>

				<v-row wrap>
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>	

				</v-row>
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section6">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Other Districts</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>	
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
				</v-row>		
				
				
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section7">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">Methology & Legend</h1>
				<v-divider></v-divider>
				<v-row wrap>
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>	

				</v-row>		
				
				
			</v-container>
		</div>

		<div data-aos="fade-in" data-aos-duration="700" id="section8">
			<v-container id="section1">
				<h1 class="text-h3 text-center pa-3">About Priest Family</h1>
				<v-divider></v-divider>
				<v-row wrap>
					
					<v-col cols="12" md="4">
						<v-img src="/profile.jpg" aspect-ratio="1.77"></v-img>
					</v-col>
					<v-col cols="12" md="8">
						<p class="text-h6">	
							{{content}}			 
						</p>
					</v-col>	
				</v-row>			
			</v-container>
		</div>


	</div>
	</div>
</template>

<script type="text/javascript">
	export default{
		data(){
			return{
				content:"The Goddess Kamakshi is in a sitting posture in the temple. This posture is called the Padmasana posture. The Padmasana posture is said to resemble a lotus. In the Yogic practice this resembles the form of meditation. The Goddess holds a Sugarcane bow on her left upper arm and Lotus, Parrot in her right upper arm. The Goddess also has divine chakras called Pasa and Angusa in her arms.The Goddess also has a Chandraperai (a shape of moon like structure) in her forehead.	"
			}
		}
	}
</script>