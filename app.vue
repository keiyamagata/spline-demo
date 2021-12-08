<template>
	<div class="wrapper">
		<header class="mainheader">
			<div class="w-12">
				<img
					src="https://scontent-bru2-1.xx.fbcdn.net/v/t39.8562-6/120009688_325579128711709_1736249742330805861_n.png?_nc_cat=1&ccb=1-5&_nc_sid=6825c5&_nc_ohc=jVykL1ais1gAX-LG-F_&_nc_ht=scontent-bru2-1.xx&oh=978facd68fb071e415c1e4a4d6f88cf3&oe=61B1D5FD"
					alt="logo messenger"
					class="w-full"
				/>
			</div>
			<div>
				<nav>
					<ul class="navList">
						<li><a href="#">Rooms</a></li>
						<li><a href="#">Features</a></li>
						<li><a href="#">Desktop App</a></li>
						<li><a href="#">Privacy and safety</a></li>
						<li><a href="#">For developers</a></li>
					</ul>
				</nav>
			</div>
		</header>
		<div class="hero">
			<iframe
				src="https://my.spline.design/messengerredesign-b5996a6ed87cc9416aa99b7eed01f82b/"
				frameborder="0"
				width="100%"
				height="100%"
			></iframe>
		</div>
		<div class="main-container">
			<div class="content">
				<h1 class="slogan">
					Hang out <br />
					anytime,<br />
					anywhere
				</h1>
				<p>
					Messenger makes it easy and fun to stay close to your favourite
					people.
				</p>
				<form>
					<input
						type="text"
						placeholder="Email address or phone number"
						class="formInput"
					/>
					<input
						type="password"
						name="password"
						id="password"
						placeholder="Password"
						class="formInput"
					/>
					<input type="submit" value="Log In" class="submitButton" />
					<a href="#" class="forgotPassword">Forgotten your password?</a><br />
					<input type="checkbox" name="signedIn" id="signedIn" />
					<label for="signedIn" class="labelSignedin">Keep me signed in</label>
				</form>
				<div class="downloads">
					<div class="linkStore">
						<img
							src="https://scontent-bru2-1.xx.fbcdn.net/v/t39.8562-6/119597221_2801552506611915_4465041091818364564_n.svg?_nc_cat=1&ccb=1-5&_nc_sid=6825c5&_nc_ohc=Swaje-Tr_WoAX8O1VwY&_nc_ht=scontent-bru2-1.xx&oh=d4d6dd414ebba1c5efee3a2f2b3a9207&oe=61B24C75"
							alt="#"
						/>
					</div>
					<div class="linkStore ml-2">
						<img
							src="https://scontent-bru2-1.xx.fbcdn.net/v/t39.8562-6/119623783_679418069326044_1960140840932205061_n.png?_nc_cat=1&ccb=1-5&_nc_sid=6825c5&_nc_ohc=XaIGjC__PfQAX_R7S3m&_nc_ht=scontent-bru2-1.xx&oh=eaccd88082f3c9bad1b877ec93c42598&oe=61B2B99D"
							alt="#"
						/>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
.wrapper {
	@apply relative;
}

.mainheader {
	@apply container mx-auto relative z-10 flex items-center justify-between;
	height: 120px;
}

.navList {
	@apply flex justify-between;
}

.navList li {
	margin-left: 30px;
	cursor: pointer;
}

.hero {
	@apply w-screen h-screen absolute top-0 left-0 z-0;
}

.main-container {
	@apply relative z-10 container mx-auto mt-10;
}

.content {
	@apply w-96 p-5 bg-gray-50 bg-opacity-40 rounded-xl backdrop-filter backdrop-blur-md border-2 border-white border-opacity-20;
}

.content p {
	@apply my-8;
}

.slogan {
	@apply inline-block text-6xl font-bold leading-normal bg-clip-text text-transparent bg-gradient-to-r from-blue-500 via-purple-600 to-red-400;
}

form {
	margin-bottom: 20px;
}

.formInput {
	@apply w-full rounded-md p-1 mb-2;
}

.submitButton {
	@apply bg-blue-500 px-5 py-2 my-8 rounded-full text-white;
}

.forgotPassword {
	@apply underline text-blue-500 ml-4 text-sm;
}

.labelSignedin {
	@apply ml-2 text-sm;
}

.linkStore {
	@apply w-28 inline-block;
}
</style>
