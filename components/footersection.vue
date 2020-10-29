<template>
	<div class="pa-3" >
		<v-divider></v-divider>
		<v-container>
			<v-row>
				<v-col cols="12" md="4">
					<v-img width="200" class="mx-auto" src="/data/sankara.jpeg"></v-img>
					<!-- <p class="text-center text-h5">Monthly News Letter</p>
					<v-text-field dense  solo label="Name" type="text"></v-text-field>
					<v-text-field  dense  solo label="Email" type="email"></v-text-field>
					<div class="mx-auto">
						<v-btn tile outlined block >Submit</v-btn>
					</div>	 -->

				</v-col>

				<v-col cols="12" md="4">
					<p class="text-center text-h5">Follow Us On </p>
					<div class="mx-auto text-center">
						<v-btn fab dark color="indigo" class="mr-1"><v-icon>mdi-facebook</v-icon></v-btn>
						<v-btn fab dark color="blue" class="mr-1"><v-icon>mdi-twitter</v-icon></v-btn>

						<v-btn fab dark color="red" class="mr-1"><v-icon>mdi-youtube</v-icon></v-btn>
						<v-btn fab dark color="pink" class="mr-1"><v-icon>mdi-instagram</v-icon></v-btn>
					</div>	
				</v-col>

				<v-col cols="12" md="4">
					<p class="text-center text-h5">Quick Links</p>
					<div class="mx-auto text-center">
							<v-list>
								<v-list-item link class="pa-1" to="/about/temple">About Temple</v-list-item>
								<v-list-item link class="pa-1" to="/data/online/">Temple Schedule</v-list-item>
								<v-list-item link class="pa-1" to="/about/futureevents">Upcoming Events</v-list-item>
								<v-list-item link class="pa-1" to="/about/howtoreach">How to Reach</v-list-item>
							</v-list>
					</div>	
				</v-col>
			</v-row>

			<v-row>
				<v-col cols="12">
					<p  class="mx-auto">Copyright © 2020. All rights reserved.

					</p>
				</v-col>
			</v-row>
		</v-container>
	</div>
</template>

<script type="text/javascript">
	export default{
		name:"footersection"
	}
</script>