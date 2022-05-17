<template>
    <div>
        <a href="#" class="js-colorlib-nav-toggle colorlib-nav-toggle" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar"><i></i></a>
		<aside id="colorlib-aside" role="complementary" class="border js-fullheight">
			<div class="text-center">
				<div class="author-img" style="background-image: url(images/profile.jpg);"></div>
				<h1 id="colorlib-logo"><a href="index.html">Alisher Okhunov</a></h1>
				<span class="position"><a href="#">Software-Engineer</a></span>
			</div>
			<nav id="colorlib-main-menu" role="navigation" class="navbar">
				<div id="navbar" class="collapse">
					<ul>
						<li><a href="#" data-nav-section="about">About</a></li>
						<li><a href="#" data-nav-section="services">Services</a></li>
						<li><a href="#" data-nav-section="skills">Skills</a></li>
						<li><a href="#" data-nav-section="education">Education</a></li>
						<li><a href="#" data-nav-section="experience">Experience</a></li>
						<li><a href="#" data-nav-section="blog">Blog</a></li>
						<li><a href="#" data-nav-section="contact">Contact</a></li>
					</ul>
				</div>
			</nav>

			<div class="colorlib-footer">
				<ul>
					<li><a href="https://www.facebook.com/alisherOhunov"><img class="social-media" src="images/facebook.png" /></a></li>
					<li><a href="https://www.instagram.com/1alisher____/"><img class="social-media" src="images/instagram.png" /></a></li>
					<li><a href="https://t.me/alisherOhunov"><img class="social-media" src="images/telegram.png" /></a></li>
					<li><a href="https://github.com/alisherOhunov"><img class="social-media" src="images/github.png" /></a></li>
				</ul>
			</div>

		</aside>
    </div>
</template>
<script>
    export default{
        name: "SideBar"
    }
</script>