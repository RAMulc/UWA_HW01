# UWA_HW01
UWA - # 01 HTML CSS Git: Code Refactor

index.html update 23/08/2020:
01		html file formatted.
02		Reduction of image file sizes to speed up page load time, file names suffixed with "_small" in html file.
		Also url in css file (line 57) updated to use smaller file size.
03		Line 29. id="search-engine-optimization" added to fix link from line 16.
04		Line 76. Self closing tag '<img>, closing tag modified.
05		'alt' text added to all images.
06		Line 7. Title updated.
07		Individual classes removed from within 'content'. css file updated to utilise 'div' entries.


style.css update 23/08/2020:
01		Images in content rationalised to single '.content img' entry.
02		'h2' in content rationalised to single '.content h2' entry.
03		Individual classes within content removed. Now makes use of the 'div' entries - '.content div'
04		Font set in '.content' class rather than sub-classes.
05		Images in benefits rationalised to single '.benefits img' entry.
06		'h3' in benefits rationalised to single '.benefits h2' entry.
07		Individual classes within benefits removed. Now makes use of the 'div' entries - '.benefits div'
08		Generally re-ordered.
09		'.header ul li' consolidated. As there is only a single list, the '.header' could be removed.

images directory:
01		File sizes for .jpg files reduced to 10% original size. What is a good size? 500kb recommended online.
		digital-marketing-meeting.jpg
		online-reputation-management.jpg
		search-engine-optimization.jpg
		social-media-marketing.jpg
