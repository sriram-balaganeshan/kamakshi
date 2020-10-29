<template>
	<div>
		<v-app-bar dark id="navbar" >
			<v-toolbar-title><v-list-item link text to="/" id="index">Home
			</v-list-item></v-toolbar-title>
			<v-spacer></v-spacer>
			<v-toolbar-items class="hidden-sm-and-down">
				
				<v-menu offset-y open-on-hover>
					<template v-slot:activator="{ on, attrs }">
						<v-btn   v-bind="attrs" v-on="on">
							Temple
						</v-btn>
					</template>
					<v-list>
						<v-list-item>
							<v-list-item-title><v-list-item  link to="/about/goddess_kamakshi">About Kamakshi</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title> <v-list-item link to="/about/temple">Temple Legend</v-list-item></v-list-item-title>
						</v-list-item>
					<!-- 	<v-list-item>
							<v-list-item-title> <v-list-item link to="/data/about#section3">History</v-list-item></v-list-item-title>
						</v-list-item> -->
						<v-list-item>
							<v-list-item-title> <v-list-item link to="/about/kanchipuram">About Kanchipuram</v-list-item></v-list-item-title>
						</v-list-item>
						<!-- <v-list-item>
							<v-list-item-title> <v-list-item link to="/data/about#section5">Other Temple</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title> <v-list-item link to="/data/about#section6">Other Districts</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title> <v-list-item link to="/data/about#section7">Methology & Legend</v-list-item></v-list-item-title>
						</v-list-item> -->
						<v-list-item>
							<v-list-item-title> <v-list-item link to="/about/priest/">About Priest Family</v-list-item></v-list-item-title>
						</v-list-item>
					</v-list>
				</v-menu>

				<v-menu offset-y open-on-hover>
					<template v-slot:activator="{ on, attrs }">
						<v-btn link to="/data/pilgrim" v-bind="attrs"v-on="on">
							Pilgrim Service
						</v-btn>
					</template>
					<v-list>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/pilgrim#section2">Sevas</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/pilgrim#section3">Prasad & Soverign</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/pilgrim#section4">Picture & Gifts</v-list-item></v-list-item-title>
						</v-list-item>
					</v-list>
				</v-menu>

				<v-menu offset-y open-on-hover>
					<template v-slot:activator="{ on, attrs }">
						<v-btn link to="/data/online"v-bind="attrs"v-on="on">
							Online Service
						</v-btn>
					</template>
					<v-list>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/online#section1">Booking for Seva</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/online#section2">Booking for Darshan</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/online#section3">Publication</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/online#section4">Donation</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/online#section5">Marriage Booking</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/online#section6">Webinars</v-list-item></v-list-item-title>
						</v-list-item>
					</v-list>
				</v-menu>

				<v-menu offset-y open-on-hover>
					<template v-slot:activator="{ on, attrs }">
						<v-btn link to="/data/news" v-bind="attrs"v-on="on">
							News & Events
						</v-btn>
					</template>
					<v-list>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/news#section1">Print</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/news#section2">Media</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/news#section3">Blog</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/news#section4">Past Event</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/data/news#section5">Future Event</v-list-item></v-list-item-title>
						</v-list-item>
					</v-list>
				</v-menu>

				<v-menu offset-y open-on-hover>
					<template v-slot:activator="{ on, attrs }">
						<v-btn v-bind="attrs"v-on="on">
							Gallery
						</v-btn>
					</template>
					<v-list>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/gallery/photos#section1">Temple Photos</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/gallery/photos#section2">Festival Photos</v-list-item></v-list-item-title>
						</v-list-item>
						<v-list-item>
							<v-list-item-title><v-list-item link to="/gallery/videos">Videos Section</v-list-item></v-list-item-title>
						</v-list-item>
				</v-list>
			</v-menu>

			<v-menu offset-y open-on-hover>
				<template v-slot:activator="{ on, attrs }">
					<v-btn v-bind="attrs"v-on="on">
						General Info
					</v-btn>
				</template>
				<v-list>
					<v-list-item>
						<v-list-item-title> <v-list-item link to="/data/general#section1">Accomadation</v-list-item></v-list-item-title>
					</v-list-item>

					<v-list-item>
						<v-list-item-title> <v-list-item link to="/data/general#section2">Transport</v-list-item></v-list-item-title>
					</v-list-item>

					<v-list-item>
						<v-list-item-title> <v-list-item link @click="dialog = !dialog" to="/about/howtoreach">How to Reach</v-list-item></v-list-item-title>
					</v-list-item>

					<v-list-item>
						<v-list-item-title> <v-list-item link to="/data/general#section4">Facilities</v-list-item></v-list-item-title>
					</v-list-item>

					<v-list-item>
						<v-list-item-title> <v-list-item link to="/data/general#section5">Help Desk</v-list-item></v-list-item-title>
					</v-list-item>

					<v-list-item>
						<v-list-item-title> <v-list-item link to="/data/general#section6">Do's & Don't</v-list-item></v-list-item-title>
					</v-list-item>

					<v-list-item>
						<v-list-item-title> <v-list-item link to="/data/general#section7">Contact Us</v-list-item></v-list-item-title>
					</v-list-item>

					<v-list-item>
						<v-list-item-title> <v-list-item link to="/data/general#section8">Timings</v-list-item></v-list-item-title>
					</v-list-item>
				</v-list>
			</v-menu>

		</v-toolbar-items>
		<v-toolbar-items class="hidden-md-and-up" @click="openmobilenav">
			<v-icon color="white">mdi-menu</v-icon>
		</v-toolbar-items>
	</v-app-bar>
</div>


</template>

<script type="text/javascript">

	export default{
		data(){
			return{
				drawer:false,
				group:null,

			}
		},
		methods:{
			openmobilenav(){
				console.log('foo')
				this.drawer = !this.drawer
			}
		}
	}
</script>

<style lang="css" scoped>

button.v-btn.v-btn--block.v-btn--flat.v-btn--text.theme--light.v-size--default{
	text-align: left;
}
aside.v-navigation-drawer.v-navigation-drawer--absolute.v-navigation-drawer--is-mobile.v-navigation-drawer--open.v-navigation-drawer--temporary.theme--light{
	height: 100vh !important;
	overflow-y: scroll !important;
}
.theme--dark.v-list-item--active:hover::before, .theme--dark.v-list-item--active::before{
	opacity: 0;
}
#index{
	color: white;
}

</style>

