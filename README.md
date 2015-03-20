# grid.css - [demo](http://cassidyjames.github.io/grid.css/)
Simple Responsive Grid Stylesheet by [@cassidyjames](https://github.com/cassidyjames).

Mobile-first with smablet- (small tablet), medium-, large-, xlarge-, and xxlarge-up overrides. Inspired slightly by both Zurb's Foundation and CSS-Tricks' grid. Similar to what's used on System76.com.

[![Example](https://cloud.githubusercontent.com/assets/611168/6745836/dcdf00a2-ce82-11e4-9caf-26864a3d73a6.png)](http://cassidyjames.github.io/grid.css/ "Click for Demo")

## Usage

Place `grid.css` in your project folder and reference it like any other stylesheet. That's about it.

## Classes

Use `.grid` as a container for grid-sized things. Similar to a "row" in Foundation or other grid systems. 

### Sizes

* `.whole`: Fill the whole width, or 100%.
* `.half`: Fill half the width, or 50%.
* `.quarter`: Fill a quarter of the width, or 25%.
* `.three-quarters`: Fill three quarters of the width, or 75%.
* `.third`: Fill one third of the width, or 33.33%.
* `.two-thirds`: Fill two thirds of the width, or 66.66%.

### Responsive display buckets

By default, all size classes apply to all display size buckets. Prepend any of the above size classes with a display size bucket to make it apply to that size and up. So `.half` would fill 50% on all displays, while `.medium-half` would fill 50% on medium-and-larger displays.

* `smablet`: 640+ px wide (typically small tablets and larger)
* `medium`: 768+ px wide (iPad-sized tablets and up)
* `large`: 1025+ px wide (typically small desktop browser and up)
* `xlarge`: 1441+ px wide (higher resolution monitors and up)
* `xxlarge`: 1921+ px wide (larger than 1080p)

## Example

These snippets would be full-width on mobile devices, split 50/50 on small and large tablet-sized displays, and split 33/67 on larger displays.

```html
<section class="grid">
	<div class="smablet-half large-third">
		<h3>UX Design</h3>
		<p>Products should be designed to be useful, usable, and desirable. I help design websites, apps, and services to meet the needs of stakeholders while keeping the design focused on the user and their experience.</p>
	</div>
	<div class="smablet-half large-two-thirds">
		<h3>Front-End Web Development</h3>
		<p>HTML, CSS, JavaScript. Bootstrap, Foundation. Light image editing. Sass, Gulp. I have the skills and experience needed to take a design concept and turn it into a working, responsive, mobile-first website. Whether you have a rough design you want refined and turned into a responsive site or a detailed mockup, I'll work with you to bring it alive.</p>
	</div>
</section>
```
