---
title: contact
include_in_nav: true
---

<p>I am almost universally Not Good At Twitter (thank goodness), so if you want to get ahold of me and don't have Mastodon or my work details, the form below is for you. In addition to being the Open Tech lead for NHS England I occasionally take on a few hours a week for consulting on technically difficult projects. Please get in touch for:</p> 
<ul>
<li>open source in healthtech</li>
<li>International Patient Summaries</li>
<li>European AI policy</li>
<li>on-hand expertise for public dialogue or futures work,</li>
<li>helping to solve heavy-math or computationally-intensive problems that tackle tomorrow's thorny challenges,</li> 
<li>work that uses the internet to make new, weird, art,</li>
<li>and lectures on climatology or the history of science and data, with a focus on the 1500s to 1800s.</li></ul> 
<p>If you'd like to hear stories about Émilie du Chatelet (gambler!) or John Napier (wizard!), feel free to ask.</p>

<p>I publish all my scientific and policy work under Andrew, and for everything else I use Dee (which I prefer). You can use either, but please don't confuse me by using one for the other, or expect me to be world famous BBC foreign correspondent, <a href="http://www.andrew-harding.com/about">Andrew Harding</a>. I have never been to Eyl and he, to the best of my knowledge, doesn't have a doctorate.
	
<form action="https://formspree.io/{{ site.email }}" method="POST">
	<div class="fields">
		<div class="field half first">
			<label for="name">Name</label>
			<input type="text" name="name" id="name" />
		</div>
		<div class="field half">
			<label for="email">Email</label>
			<input type="text" name="_replyto" id="email" />
		</div>
		<div class="field">
			<label for="message">Message</label>
			<textarea name="message" id="message" rows="4"></textarea>
		</div>
	</div>
	<ul class="actions">
		<li><input type="submit" value="Send Message" class="primary" /></li>
		<li><input type="reset" value="Reset" /></li>
	</ul>
</form>
<ul class="icons">

	{% if site.twitter_url %}
				<li><a href="{{ site.twitter_url }}" class="icon fa-twitter" target="_blank"><span class="label">Twitter</span></a></li>
				{% endif %}
				{% if site.googleplus_url %}
				<li><a href="{{ site.googleplus_url }}" class="icon fa-google-plus" target="_blank"><span class="label">Google+</span></a></li>
				{% endif %}
				{% if site.facebook_url %}
				<li><a href="{{ site.facebook_url }}" class="icon fa-facebook" target="_blank"><span class="label">Facebook</span></a></li>
				{% endif %}
				{% if site.instagram_url %}
				<li><a href="{{ site.instagram_url }}" class="icon fa-instagram" target="_blank"><span class="label">Instagram</span></a></li>
				{% endif %}
				{% if site.pinterest_url %}
				<li><a href="{{ site.pinterest_url }}" class="icon fa-pinterest" target="_blank"><span class="label">Pinterest</span></a></li>
				{% endif %}
				{% if site.gitlab_url %}
				<li><a href="{{ site.gitlab_url }}" class="icon fa-gitlab" target="_blank"><span class="label">GitLab</span></a></li>
				{% endif %}
				{% if site.github_url %}
				<li><a href="{{ site.github_url }}" class="icon fa-github" target="_blank"><span class="label">GitHub</span></a></li>
				{% endif %}
				{% if site.slack_url %}
				<li><a href="{{ site.slack_url }}" class="icon fa-slack" target="_blank"><span class="label">Slack</span></a></li>
				{% endif %}
				{% if site.flickr_url %}
				<li><a href="{{ site.flickr_url }}" class="icon fa-flickr" target="_blank"><span class="label">Slack</span></a></li>
				{% endif %}
				{% if site.medium_url %}
				<li><a href="{{ site.medium_url }}" class="icon fa-medium" target="_blank"><span class="label">Slack</span></a></li>
				{% endif %}
				{% if site.linkedin_url %}
				<li><a href="{{ site.linkedin_url }}" class="icon fa-linkedin" target="_blank"><span class="label">LinkedIn</span></a></li>
				{% endif %}
				{% if site.keybase_url %}
				<li><a href="{{ site.keybase_url }}" class="icon fa-key" target="_blank"><span class="label">Keybase</span></a></li>
				{% endif %}
				{% if site.reddit_url %}
				<li><a href="{{ site.reddit_url }}" class="icon fa-reddit" target="_blank"><span class="label">Reddit</span></a></li>
				{% endif %}
				{% if site.stackoverflow_url %}
				<li><a href="{{ site.stackoverflow_url }}" class="icon fa-stack-overflow" target="_blank"><span class="label">Stackoverflow</span></a></li>
				{% endif %}
				{% if site.spotify_url %}
				<li><a href="{{ site.spotify_url }}" class="icon fa-spotify" target="_blank"><span class="label">Spotify</span></a></li>
				{% endif %}

</ul>
