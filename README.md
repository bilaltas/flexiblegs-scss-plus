# [flexiblegs-scss-plus](http://flexible.gs)

Flexible Grid System Scss Plus

## Install

### [Download](https://raw.githubusercontent.com/flexiblegs/flexiblegs-scss-plus/master/scss/helper/flexiblegs-scss-plus.scss)
```scss
$flexiblegs-method: (
  "css",
  "bem"
);
$flexiblegs-breakpoint: (
  "xl" : "",
  "lg" : "(max-width: 1024px)",
  "md" : "(max-width: 768px)",
  "sm" : "(max-width: 667px)"
);
$wrap-col: (
  "auto", 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12
);
$wrap-prop: (
  "table",
  "flexbox",
  "normal",
  "left",
  "center",
  "right",
  "top",
  "middle",
  "bottom",
  "between",
  "around",
  "baseline",
  "reverse",
  "not-reverse"
);
$col-row: (
  1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12
);
$custom-sizeables: (

	// Single CSS
	"width" : (
		(25, 50, 100) : (
			"width" : %,
		)
	),
	"height" : (
		(100, 300, 500) : (
			"height" : px,
		)
	),


	"fsize" : (
		(14, 19, 22) : (
			"font-size" : px
		)
	),

	// With value shortcuts
	"fontsize" : (
		(
			"small"  : "0.7",
			"medium" : "1",
			"large"  : "1.5"
		) : (
			"font-size" : em
		)
	),


	// Without value suffix
	"fontweight" : (
		(normal, bold, 900) : (
			"font-weight"
		)
	),

	"align" : (
		(left, right, center, justify) : (
			"text-align",
		)
	),


	// With multiple CSS
	"paddingx" : (
		(0, 8, 16) : (
			"padding-left" : px,
			"padding-right" : px
		)
	),
	"marginy" : (
		(0, 8, 16) : (
			"margin-top" : px,
			"margin-bottom" : px
		)
	)

);
$col-prop: (
  "hidden",
  "not-hidden",
  "first",
  "not-first",
  "last",
  "not-last"
);
$wrap-gutter: (
  0, 8, 16, 24, 40
);
$wrap-outside: (
  0, 8, 16, 24, 40
);
$wrap-masonry: (
  2, 3, 4, 5, 6
);

@import "flexiblegs-scss";
@import "flexiblegs-scss-plus";
```

### [npm](https://www.npmjs.com/package/flexiblegs-scss-plus)
```
$ npm install --save flexiblegs-scss-plus
```

### [bower](http://bower.io/search/?q=flexiblegs-scss-plus)
```
$ bower install --save flexiblegs-scss-plus
```

## Contributing
1. Fork it ( https://github.com/flexiblegs/flexiblegs-scss-plus/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## License
- Flexible Grid System is licensed under the MIT license.
  - [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)
- Flexible Grid System documentation is licensed under a Creative Commons Attribution 4.0 International License.
  - [http://creativecommons.org/licenses/by/4.0](http://creativecommons.org/licenses/by/4.0)
