+++
# Hero widget.
widget = "hero"
active = true
date = 2017-10-15

title = "Jonathan Pirro"

# Order that this section will appear in.
weight = 3

# Overlay a color or image (optional).
#   Deactivate an option by commenting out the line, prefixing it with `#`.
[header]
  bg_images = [
    "img/bg/IMG_1600.jpg",
    "img/bg/IMG_4672.jpg",
    "img/bg/IMG_5335.jpg",
    "img/bg/IMG_6929.jpg"
  ]
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/bubbles-wide.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

# Call to action button (optional).
#   Activate the button by specifying a URL and button label below.
#   Deactivate by commenting out parameters, prefixing lines with `#`.
[cta]
  url = "./post/getting-started/"
  label = '<i class="fa fa-camera"></i> SmugMug'
+++

Concert/event/wedding photographer. DevOps engineer and documentation expert. Professional weirdo.
<!-- <br>
<small><a id="academic-release" href="https://sourcethemes.com/academic/tags/updates">updates</a></small> 
<br><br>
<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=gcushen&amp;repo=hugo-academic&amp;type=star&amp;count=true&amp;size=large" scrolling="0" width="160px" height="30px" frameborder="0"></iframe>
<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=gcushen&amp;repo=hugo-academic&amp;type=fork&amp;count=true&amp;size=large" scrolling="0" width="158px" height="30px" frameborder="0"></iframe> -->

<script type="text/javascript">
  (function defer() {
    if (window.jQuery) {
      jQuery(document).ready(function(){
        GetLatestReleaseInfo();
      });
    } else {
      setTimeout(function() { defer() }, 50);
    }
  })();  
  function GetLatestReleaseInfo() {
    $.getJSON('https://api.github.com/repos/gcushen/hugo-academic/tags').done(function (json) {
      let release = json[0];
      // let downloadURL = release.zipball_url;
      $('#academic-release').text('Latest release ' + release.name);  
    });    
}  
</script>
