@import url("https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,300italic,400,600");
@import url("font-awesome.min.css");

/*
	Overflow by HTML5 UP
	html5up.net | @ajlkn
	Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
*/

html, body, div, span, applet, object,
iframe, h1, h2, h3, h4, h5, h6, p, blockquote,
pre, a, abbr, acronym, address, big, cite,
code, del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var, b,
u, i, center, dl, dt, dd, ol, ul, li, fieldset,
form, label, legend, table, caption, tbody,
tfoot, thead, tr, th, td, article, aside,
canvas, details, embed, figure, figcaption,
footer, header, hgroup, menu, nav, output, ruby,
section, summary, time, mark, audio, video 
{
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}

article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section 
{
	display: block;
}

body 
{
	line-height: 1;
}


ol, ul 
{
	list-style: none;
}


blockquote, q
{
	quotes: none;
}

	blockquote:before, blockquote:after, q:before, q:after 
	{
		content: '';
		content: none;
	}

table 
{
	border-collapse: collapse;
	border-spacing: 0;
}

body 
{
	-webkit-text-size-adjust: none;
}

mark 
{
	background-color: transparent;
	color: inherit;
}

input::-moz-focus-inner
{
	border: 0;
	padding: 0;
}

input, select, textarea {
	-moz-appearance: none;
	-webkit-appearance: none;
	-ms-appearance: none;
	appearance: none;
}

/* Basic */

	html 
	{
		box-sizing: border-box;
	}

	*, *:before, *:after {
		box-sizing: inherit;
	}

	body
	{
		background-color: #183026;
		background-image: url("images/overlay.png"), url("../../images/bg.jpg");
		background-repeat: repeat, no-repeat;
		background-size: auto, cover;
		background-position: top left, center 0;
		background-attachment: fixed, fixed;
		font-family: 'Source Sans Pro', sans-serif;
		font-size: 18pt;
		line-height: 1.75em;
		font-weight: 300;
		letter-spacing: 1px;
		color: #3a3939;
		text-shadow: 0 0 0.5px rgba(58, 57, 57, 0.25);
		-webkit-text-stroke: 0.25px;
	}

		body.is-scroll {
			background-attachment: scroll, scroll;
			background-size: auto, 100% auto;
		}

		body.is-preload *, body.is-preload *:before, body.is-preload *:after
		 {
			-moz-animation: none !important;
			-webkit-animation: none !important;
			-ms-animation: none !important;
			animation: none !important;
			-moz-transition: none !important;
			-webkit-transition: none !important;
			-ms-transition: none !important;
			transition: none !important;
		}

	input, textarea, select {
		font-family: 'Source Sans Pro', sans-serif;
		font-size: 18pt;
		line-height: 1.75em;
		font-weight: 300;
		letter-spacing: 1px;
		color: #3a3939;
		text-shadow: 0 0 0.5px rgba(58, 57, 57, 0.25);
		-webkit-text-stroke: 0.25px;
	}

	h1, h2, h3, h4, h5, h6 {
		font-weight: 400;
		text-transform: uppercase;
		line-height: 1.75em;
	}

	h1 a, h2 a, h3 a, h4 a, h5 a, h6 a {
		color: inherit;
		text-decoration: none;
	}

	h2 {
		font-size: 1.25em;
		letter-spacing: 8px;
	}

	h3 {
		font-size: 1em;
		letter-spacing: 5px;
	}

	strong, b {
		font-weight: 400;
	}

	em, i {
		font-style: italic;
	}

	a 
	{
		-moz-transition: border-color 0.35s ease-in-out, color 0.35s ease-in-out;
		-webkit-transition: border-color 0.35s ease-in-out, color 0.35s ease-in-out;
		-ms-transition: border-color 0.35s ease-in-out, color 0.35s ease-in-out;
		transition: border-color 0.35s ease-in-out, color 0.35s ease-in-out;
		color: #35b88f;
		text-shadow: 0 0 0.5px rgba(53, 184, 143, 0.25);
		text-decoration: none;
		border-bottom: dotted 1px rgba(53, 184, 143, 0.5);
	}

		a:hover {
			border-bottom-color: rgba(53, 184, 143, 0);
		}

	sub {
		position: relative;
		top: 0.5em;
		font-size: 0.8em;
	}

	sup {
		position: relative;
		top: -0.5em;
		font-size: 0.8em;
	}

	hr {
		border: 0;
		border-top: solid 1px #dad9d9;
		margin: 2em 0 2em 0;
	}

	blockquote {
		border-left: solid 0.5em #eae9e9;
		padding: 1em 0 1em 2em;
		font-style: italic;
	}

	p, ul, ol, dl, table {
		margin-bottom: 1em;
	}

	header {
		margin-bottom: 1em;
	}

		header p {
			display: block;
			margin: 0.5em 0 0 0;
			padding: 0 0 1.5em 0;
		}

	footer {
		margin-top: 1em;
	}

	br.clear {
		clear: both;
	}

/* Container */

	.container {
		margin: 0 auto;
		max-width: 100%;
		width: 1140px;
	}

		@media screen and (max-width: 1680px) {

			.container {
				width: 960px;
			}

		}

		@media screen and (max-width: 1080px) {

			.container {
				width: 95%;
			}

		}

/* Row */

	.row {
		display: flex;
		flex-wrap: wrap;
		box-sizing: border-box;
		align-items: stretch;
	}

		.row > * {
			box-sizing: border-box;
		}

		.row.gtr-uniform > * > :last-child {
			margin-bottom: 0;
		}

		.row.aln-left {
			justify-content: flex-start;
		}

		.row.aln-center {
			justify-content: center;
		}

		.row.aln-right {
			justify-content: flex-end;
		}

		.row.aln-top {
			align-items: flex-start;
		}

		.row.aln-middle {
			align-items: center;
		}

		.row.aln-bottom {
			align-items: flex-end;
		}

		.row > .imp {
			order: -1;
		}

		.row > .col-1 {
			width: 8.3333333333%;
		}

		.row > .off-1 {
			margin-left: 8.3333333333%;
		}

		.row > .col-2 {
			width: 16.6666666667%;
		}

		.row > .off-2 {
			margin-left: 16.6666666667%;
		}

		.row > .col-3 {
			width: 25%;
		}

		.row > .off-3 {
			margin-left: 25%;
		}

		.row > .col-4 {
			width: 33.3333333333%;
		}

		.row > .off-4 {
			margin-left: 33.3333333333%;
		}

		.row > .col-5 {
			width: 41.6666666667%;
		}

		.row > .off-5 {
			margin-left: 41.6666666667%;
		}

		.row > .col-6 {
			width: 50%;
		}

		.row > .off-6 {
			margin-left: 50%;
		}

		.row > .col-7 {
			width: 58.3333333333%;
		}

		.row > .off-7 {
			margin-left: 58.3333333333%;
		}

		.row > .col-8 {
			width: 66.6666666667%;
		}

		.row > .off-8 {
			margin-left: 66.6666666667%;
		}

		.row > .col-9 {
			width: 75%;
		}

		.row > .off-9 {
			margin-left: 75%;
		}

		.row > .col-10 {
			width: 83.3333333333%;
		}

		.row > .off-10 {
			margin-left: 83.3333333333%;
		}

		.row > .col-11 {
			width: 91.6666666667%;
		}

		.row > .off-11 {
			margin-left: 91.6666666667%;
		}

		.row > .col-12 {
			width: 100%;
		}

		.row > .off-12 {
			margin-left: 100%;
		}

		.row.gtr-0 {
			margin-top: 0px;
			margin-left: 0px;
		}

			.row.gtr-0 > * {
				padding: 0px 0 0 0px;
			}

			.row.gtr-0.gtr-uniform {
				margin-top: 0px;
			}

				.row.gtr-0.gtr-uniform > * {
					padding-top: 0px;
				}

		.row.gtr-25 {
			margin-top: -10px;
			margin-left: -10px;
		}

			.row.gtr-25 > * {
				padding: 10px 0 0 10px;
			}

			.row.gtr-25.gtr-uniform {
				margin-top: -10px;
			}

				.row.gtr-25.gtr-uniform > * {
					padding-top: 10px;
				}

		.row.gtr-50 {
			margin-top: -20px;
			margin-left: -20px;
		}

			.row.gtr-50 > * {
				padding: 20px 0 0 20px;
			}

			.row.gtr-50.gtr-uniform {
				margin-top: -20px;
			}

				.row.gtr-50.gtr-uniform > * {
					padding-top: 20px;
				}

		.row {
			margin-top: -40px;
			margin-left: -40px;
		}

			.row > * {
				padding: 40px 0 0 40px;
			}

			.row.gtr-uniform {
				margin-top: -40px;
			}

				.row.gtr-uniform > * {
					padding-top: 40px;
				}

		.row.gtr-150 {
			margin-top: -60px;
			margin-left: -60px;
		}

			.row.gtr-150 > * {
				padding: 60px 0 0 60px;
			}

			.row.gtr-150.gtr-uniform {
				margin-top: -60px;
			}

				.row.gtr-150.gtr-uniform > * {
					padding-top: 60px;
				}

		.row.gtr-200 {
			margin-top: -80px;
			margin-left: -80px;
		}

			.row.gtr-200 > * {
				padding: 80px 0 0 80px;
			}

			.row.gtr-200.gtr-uniform {
				margin-top: -80px;
			}

				.row.gtr-200.gtr-uniform > * {
					padding-top: 80px;
				}

		@media screen and (max-width: 1680px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-wide {
					order: -1;
				}

				.row > .col-1-wide {
					width: 8.3333333333%;
				}

				.row > .off-1-wide {
					margin-left: 8.3333333333%;
				}

				.row > .col-2-wide {
					width: 16.6666666667%;
				}

				.row > .off-2-wide {
					margin-left: 16.6666666667%;
				}

				.row > .col-3-wide {
					width: 25%;
				}

				.row > .off-3-wide {
					margin-left: 25%;
				}

				.row > .col-4-wide {
					width: 33.3333333333%;
				}

				.row > .off-4-wide {
					margin-left: 33.3333333333%;
				}

				.row > .col-5-wide {
					width: 41.6666666667%;
				}

				.row > .off-5-wide {
					margin-left: 41.6666666667%;
				}

				.row > .col-6-wide {
					width: 50%;
				}

				.row > .off-6-wide {
					margin-left: 50%;
				}

				.row > .col-7-wide {
					width: 58.3333333333%;
				}

				.row > .off-7-wide {
					margin-left: 58.3333333333%;
				}

				.row > .col-8-wide {
					width: 66.6666666667%;
				}

				.row > .off-8-wide {
					margin-left: 66.6666666667%;
				}

				.row > .col-9-wide {
					width: 75%;
				}

				.row > .off-9-wide {
					margin-left: 75%;
				}

				.row > .col-10-wide {
					width: 83.3333333333%;
				}

				.row > .off-10-wide {
					margin-left: 83.3333333333%;
				}

				.row > .col-11-wide {
					width: 91.6666666667%;
				}

				.row > .off-11-wide {
					margin-left: 91.6666666667%;
				}

				.row > .col-12-wide {
					width: 100%;
				}

				.row > .off-12-wide {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0px;
					margin-left: 0px;
				}

					.row.gtr-0 > * {
						padding: 0px 0 0 0px;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0px;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0px;
						}

				.row.gtr-25 {
					margin-top: -10px;
					margin-left: -10px;
				}

					.row.gtr-25 > * {
						padding: 10px 0 0 10px;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -10px;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 10px;
						}

				.row.gtr-50 {
					margin-top: -20px;
					margin-left: -20px;
				}

					.row.gtr-50 > * {
						padding: 20px 0 0 20px;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -20px;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 20px;
						}

				.row {
					margin-top: -40px;
					margin-left: -40px;
				}

					.row > * {
						padding: 40px 0 0 40px;
					}

					.row.gtr-uniform {
						margin-top: -40px;
					}

						.row.gtr-uniform > * {
							padding-top: 40px;
						}

				.row.gtr-150 {
					margin-top: -60px;
					margin-left: -60px;
				}

					.row.gtr-150 > * {
						padding: 60px 0 0 60px;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -60px;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 60px;
						}

				.row.gtr-200 {
					margin-top: -80px;
					margin-left: -80px;
				}

					.row.gtr-200 > * {
						padding: 80px 0 0 80px;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -80px;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 80px;
						}

		}

		@media screen and (max-width: 1080px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-normal {
					order: -1;
				}

				.row > .col-1-normal {
					width: 8.3333333333%;
				}

				.row > .off-1-normal {
					margin-left: 8.3333333333%;
				}

				.row > .col-2-normal {
					width: 16.6666666667%;
				}

				.row > .off-2-normal {
					margin-left: 16.6666666667%;
				}

				.row > .col-3-normal {
					width: 25%;
				}

				.row > .off-3-normal {
					margin-left: 25%;
				}

				.row > .col-4-normal {
					width: 33.3333333333%;
				}

				.row > .off-4-normal {
					margin-left: 33.3333333333%;
				}

				.row > .col-5-normal {
					width: 41.6666666667%;
				}

				.row > .off-5-normal {
					margin-left: 41.6666666667%;
				}

				.row > .col-6-normal {
					width: 50%;
				}

				.row > .off-6-normal {
					margin-left: 50%;
				}

				.row > .col-7-normal {
					width: 58.3333333333%;
				}

				.row > .off-7-normal {
					margin-left: 58.3333333333%;
				}

				.row > .col-8-normal {
					width: 66.6666666667%;
				}

				.row > .off-8-normal {
					margin-left: 66.6666666667%;
				}

				.row > .col-9-normal {
					width: 75%;
				}

				.row > .off-9-normal {
					margin-left: 75%;
				}

				.row > .col-10-normal {
					width: 83.3333333333%;
				}

				.row > .off-10-normal {
					margin-left: 83.3333333333%;
				}

				.row > .col-11-normal {
					width: 91.6666666667%;
				}

				.row > .off-11-normal {
					margin-left: 91.6666666667%;
				}

				.row > .col-12-normal {
					width: 100%;
				}

				.row > .off-12-normal {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0px;
					margin-left: 0px;
				}

					.row.gtr-0 > * {
						padding: 0px 0 0 0px;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0px;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0px;
						}

				.row.gtr-25 {
					margin-top: -10px;
					margin-left: -10px;
				}

					.row.gtr-25 > * {
						padding: 10px 0 0 10px;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -10px;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 10px;
						}

				.row.gtr-50 {
					margin-top: -20px;
					margin-left: -20px;
				}

					.row.gtr-50 > * {
						padding: 20px 0 0 20px;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -20px;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 20px;
						}

				.row {
					margin-top: -40px;
					margin-left: -40px;
				}

					.row > * {
						padding: 40px 0 0 40px;
					}

					.row.gtr-uniform {
						margin-top: -40px;
					}

						.row.gtr-uniform > * {
							padding-top: 40px;
						}

				.row.gtr-150 {
					margin-top: -60px;
					margin-left: -60px;
				}

					.row.gtr-150 > * {
						padding: 60px 0 0 60px;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -60px;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 60px;
						}

				.row.gtr-200 {
					margin-top: -80px;
					margin-left: -80px;
				}

					.row.gtr-200 > * {
						padding: 80px 0 0 80px;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -80px;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 80px;
						}

		}

		@media screen and (max-width: 840px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-narrow {
					order: -1;
				}

				.row > .col-1-narrow {
					width: 8.3333333333%;
				}

				.row > .off-1-narrow {
					margin-left: 8.3333333333%;
				}

				.row > .col-2-narrow {
					width: 16.6666666667%;
				}

				.row > .off-2-narrow {
					margin-left: 16.6666666667%;
				}

				.row > .col-3-narrow {
					width: 25%;
				}

				.row > .off-3-narrow {
					margin-left: 25%;
				}

				.row > .col-4-narrow {
					width: 33.3333333333%;
				}

				.row > .off-4-narrow {
					margin-left: 33.3333333333%;
				}

				.row > .col-5-narrow {
					width: 41.6666666667%;
				}

				.row > .off-5-narrow {
					margin-left: 41.6666666667%;
				}

				.row > .col-6-narrow {
					width: 50%;
				}

				.row > .off-6-narrow {
					margin-left: 50%;
				}

				.row > .col-7-narrow {
					width: 58.3333333333%;
				}

				.row > .off-7-narrow {
					margin-left: 58.3333333333%;
				}

				.row > .col-8-narrow {
					width: 66.6666666667%;
				}

				.row > .off-8-narrow {
					margin-left: 66.6666666667%;
				}

				.row > .col-9-narrow {
					width: 75%;
				}

				.row > .off-9-narrow {
					margin-left: 75%;
				}

				.row > .col-10-narrow {
					width: 83.3333333333%;
				}

				.row > .off-10-narrow {
					margin-left: 83.3333333333%;
				}

				.row > .col-11-narrow {
					width: 91.6666666667%;
				}

				.row > .off-11-narrow {
					margin-left: 91.6666666667%;
				}

				.row > .col-12-narrow {
					width: 100%;
				}

				.row > .off-12-narrow {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0px;
					margin-left: 0px;
				}

					.row.gtr-0 > * {
						padding: 0px 0 0 0px;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0px;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0px;
						}

				.row.gtr-25 {
					margin-top: -7.5px;
					margin-left: -7.5px;
				}

					.row.gtr-25 > * {
						padding: 7.5px 0 0 7.5px;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -7.5px;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 7.5px;
						}

				.row.gtr-50 {
					margin-top: -15px;
					margin-left: -15px;
				}

					.row.gtr-50 > * {
						padding: 15px 0 0 15px;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -15px;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 15px;
						}

				.row {
					margin-top: -30px;
					margin-left: -30px;
				}

					.row > * {
						padding: 30px 0 0 30px;
					}

					.row.gtr-uniform {
						margin-top: -30px;
					}

						.row.gtr-uniform > * {
							padding-top: 30px;
						}

				.row.gtr-150 {
					margin-top: -45px;
					margin-left: -45px;
				}

					.row.gtr-150 > * {
						padding: 45px 0 0 45px;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -45px;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 45px;
						}

				.row.gtr-200 {
					margin-top: -60px;
					margin-left: -60px;
				}

					.row.gtr-200 > * {
						padding: 60px 0 0 60px;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -60px;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 60px;
						}

		}

		@media screen and (max-width: 736px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-mobile {
					order: -1;
				}

				.row > .col-1-mobile {
					width: 8.3333333333%;
				}

				.row > .off-1-mobile {
					margin-left: 8.3333333333%;
				}

				.row > .col-2-mobile {
					width: 16.6666666667%;
				}

				.row > .off-2-mobile {
					margin-left: 16.6666666667%;
				}

				.row > .col-3-mobile {
					width: 25%;
				}

				.row > .off-3-mobile {
					margin-left: 25%;
				}

				.row > .col-4-mobile {
					width: 33.3333333333%;
				}

				.row > .off-4-mobile {
					margin-left: 33.3333333333%;
				}

				.row > .col-5-mobile {
					width: 41.6666666667%;
				}

				.row > .off-5-mobile {
					margin-left: 41.6666666667%;
				}

				.row > .col-6-mobile {
					width: 50%;
				}

				.row > .off-6-mobile {
					margin-left: 50%;
				}

				.row > .col-7-mobile {
					width: 58.3333333333%;
				}

				.row > .off-7-mobile {
					margin-left: 58.3333333333%;
				}

				.row > .col-8-mobile {
					width: 66.6666666667%;
				}

				.row > .off-8-mobile {
					margin-left: 66.6666666667%;
				}

				.row > .col-9-mobile {
					width: 75%;
				}

				.row > .off-9-mobile {
					margin-left: 75%;
				}

				.row > .col-10-mobile {
					width: 83.3333333333%;
				}

				.row > .off-10-mobile {
					margin-left: 83.3333333333%;
				}

				.row > .col-11-mobile {
					width: 91.6666666667%;
				}

				.row > .off-11-mobile {
					margin-left: 91.6666666667%;
				}

				.row > .col-12-mobile {
					width: 100%;
				}

				.row > .off-12-mobile {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0px;
					margin-left: 0px;
				}

					.row.gtr-0 > * {
						padding: 0px 0 0 0px;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0px;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0px;
						}

				.row.gtr-25 {
					margin-top: -5px;
					margin-left: -5px;
				}

					.row.gtr-25 > * {
						padding: 5px 0 0 5px;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -5px;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 5px;
						}

				.row.gtr-50 {
					margin-top: -10px;
					margin-left: -10px;
				}

					.row.gtr-50 > * {
						padding: 10px 0 0 10px;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -10px;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 10px;
						}

				.row {
					margin-top: -20px;
					margin-left: -20px;
				}

					.row > * {
						padding: 20px 0 0 20px;
					}

					.row.gtr-uniform {
						margin-top: -20px;
					}

						.row.gtr-uniform > * {
							padding-top: 20px;
						}

				.row.gtr-150 {
					margin-top: -30px;
					margin-left: -30px;
				}

					.row.gtr-150 > * {
						padding: 30px 0 0 30px;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -30px;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 30px;
						}

				.row.gtr-200 {
					margin-top: -40px;
					margin-left: -40px;
				}

					.row.gtr-200 > * {
						padding: 40px 0 0 40px;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -40px;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 40px;
						}

		}

/* Sections/Article */

	section, article {
		margin-bottom: 3em;
	}

	section > :last-child,
	article > :last-child,
	section:last-child,
	article:last-child {
		margin-bottom: 0;
	}

	.row > section, .row > article {
		margin-bottom: 0;
	}

/* Image */

	.image {
		display: inline-block;
		border: 0;
	}

		.image img {
			display: block;
			width: 100%;
		}

		.image.featured {
			display: block;
			width: 100%;
			margin: 0 0 2em 0;
		}

		.image.fit {
			display: block;
			width: 100%;
		}

		.image.left {
			float: left;
			margin: 0 2em 2em 0;
		}

		.image.centered {
			display: block;
			margin: 0 0 2em 0;
		}

			.image.centered img {
				margin: 0 auto;
				width: auto;
			}

/* List */

	ul {
		list-style: disc;
		padding-left: 1em;
	}

		ul li {
			padding-left: 1.5em;
			margin-top: 1.5em;
		}

			ul li:first-child {
				margin-top: 0;
			}

	ol {
		list-style: decimal;
		padding-left: 1.25em;
	}

		ol li {
			padding-left: 1.25em;
			margin-top: 1.5em;
		}

/* Icons */

	ul.icons {
		cursor: default;
		list-style: none;
		padding-left: 0;
	}

		ul.icons li {
			display: inline-block;
			padding-left: 0;
			margin-top: 0;
		}

		ul.icons a {
			display: inline-block;
			width: 2.5em;
			height: 2.5em;
			line-height: 2.5em;
			text-align: center;
			border: 0;
		}

/* Menu */

	ul.menu {
		cursor: default;
		list-style: none;
		padding-left: 0;
	}

		ul.menu li {
			display: inline-block;
			line-height: 1em;
			border-left: solid 1px #dad9d9;
			padding: 0 0 0 0.5em;
			margin: 0 0 0 0.5em;
		}

			ul.menu li:first-child {
				border-left: 0;
				padding-left: 0;
				margin-left: 0;
			}

/* Actions */

	ul.actions {
		cursor: default;
		list-style: none;
		padding-left: 0;
	}

		ul.actions li {
			display: inline-block;
			margin: 0 0 0 0.5em;
			padding-left: 0;
			margin-top: 0;
		}

			ul.actions li:first-child {
				margin-left: 0;
			}

/* Form */

	form label {
		display: block;
		margin: 0 0 0.5em 0;
	}

	form input[type="text"],
	form input[type="email"],
	form input[type="password"],
	form select,
	form textarea {
		-moz-transition: background-color 0.35s ease-in-out;
		-webkit-transition: background-color 0.35s ease-in-out;
		-ms-transition: background-color 0.35s ease-in-out;
		transition: background-color 0.35s ease-in-out;
		-webkit-appearance: none;
		display: block;
		border: 0;
		background: #f1f1f1;
		width: 100%;
		padding: 0.75em;
	}

		form input[type="text"]:focus,
		form input[type="email"]:focus,
		form input[type="password"]:focus,
		form select:focus,
		form textarea:focus {
			background-color: #f8f8f8;
		}

	form input[type="text"],
	form input[type="email"],
	form input[type="password"],
	form select {
		line-height: 1em;
	}

	form select {
		background-size: 1.25em;
		background-repeat: no-repeat;
		background-position: calc(100% - 1em) center;
		padding-right: 1.25em;
		text-overflow: ellipsis;
		background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='40' height='40' preserveAspectRatio='none' viewBox='0 0 40 40'%3E%3Cpath d='M9.4,12.3l10.4,10.4l10.4-10.4c0.2-0.2,0.5-0.4,0.9-0.4c0.3,0,0.6,0.1,0.9,0.4l3.3,3.3c0.2,0.2,0.4,0.5,0.4,0.9 c0,0.4-0.1,0.6-0.4,0.9L20.7,31.9c-0.2,0.2-0.5,0.4-0.9,0.4c-0.3,0-0.6-0.1-0.9-0.4L4.3,17.3c-0.2-0.2-0.4-0.5-0.4-0.9 c0-0.4,0.1-0.6,0.4-0.9l3.3-3.3c0.2-0.2,0.5-0.4,0.9-0.4S9.1,12.1,9.4,12.3z' fill='%235a5959' /%3E%3C/svg%3E");
	}

		form select option {
			color: #3a3939;
			background: #ffffff;
		}

		form select:focus::-ms-value {
			background-color: transparent;
		}

		form select::-ms-expand {
			display: none;
		}

	form textarea {
		min-height: 12em;
	}

	form ::-webkit-input-placeholder {
		color: #5a5959 !important;
	}

	form :-moz-placeholder {
		color: #5a5959 !important;
	}

	form ::-moz-placeholder {
		color: #5a5959 !important;
	}

	form :-ms-input-placeholder {
		color: #5a5959 !important;
	}

	form ::-moz-focus-inner {
		border: 0;
	}

	form ul.actions {
		margin-bottom: 0;
		text-align: center;
	}

/* Table */

	.table-wrapper {
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
	}

	table {
		width: 100%;
	}

		table tbody tr {
			border-top: solid 1px #eae9e9;
		}

			table tbody tr:first-child {
				border-top: 0;
			}

		table td {
			padding: 0.75em 1.25em 0.75em 1.25em;
		}

		table th {
			text-align: left;
			font-weight: 400;
			padding: 0.75em 1.25em 0.75em 1.25em;
		}

		table thead {
			background: #f5f5f5;
		}

/* Button */

	input[type="button"],
	input[type="submit"],
	input[type="reset"],
	button,
	.button {
		-moz-transition: background-color 0.35s ease-in-out, color 0.35s ease-in-out;
		-webkit-transition: background-color 0.35s ease-in-out, color 0.35s ease-in-out;
		-ms-transition: background-color 0.35s ease-in-out, color 0.35s ease-in-out;
		transition: background-color 0.35s ease-in-out, color 0.35s ease-in-out;
		-webkit-appearance: none;
		position: relative;
		display: inline-block;
		border: 0;
		background: #35b88f;
		color: #fff;
		text-shadow: 0 0 0.5px rgba(255, 255, 255, 0.25);
		cursor: pointer;
		text-decoration: none;
		outline: 0;
		padding: 1em 3em 1em 3em;
		text-align: center;
		border-radius: 3em;
		font-weight: 400;
	}

		input[type="button"]:hover,
		input[type="submit"]:hover,
		input[type="reset"]:hover,
		button:hover,
		.button:hover {
			background: #45c89f;
		}

		input[type="button"].style2,
		input[type="submit"].style2,
		input[type="reset"].style2,
		button.style2,
		.button.style2 {
			color: #3a3939;
			background: #fff;
			box-shadow: inset 0 0 0 1px #fff;
		}

			input[type="button"].style2:hover,
			input[type="submit"].style2:hover,
			input[type="reset"].style2:hover,
			button.style2:hover,
			.button.style2:hover {
				background: rgba(255, 255, 255, 0.1);
				color: #fff !important;
				text-shadow: 0 0 0.5px rgba(255, 255, 255, 0.25) !important;
			}

		input[type="button"].style3,
		input[type="submit"].style3,
		input[type="reset"].style3,
		button.style3,
		.button.style3 {
			background: none;
			color: #3a3939;
			box-shadow: inset 0 0 0 1px #dad9d9;
		}

			input[type="button"].style3:hover,
			input[type="submit"].style3:hover,
			input[type="reset"].style3:hover,
			button.style3:hover,
			.button.style3:hover {
				background: rgba(58, 57, 57, 0.025);
			}

/* Box */

	.box {
		position: relative;
		margin-top: 9em;
		margin-bottom: 0;
	}

		.box:after {
			content: '';
			display: block;
			position: absolute;
			top: -9em;
			left: 50%;
			height: 9em;
			border-left: solid 1px #fff;
		}

		.box:before {
			content: '';
			display: block;
			width: 90px;
			height: 66px;
			position: absolute;
			left: 50%;
			top: -4.5em;
			margin-left: -45px;
			margin-top: -33px;
			background: url("images/arrow.svg") no-repeat;
		}

		.box :last-child {
			margin-bottom: 0;
		}

		.box.style1 {
			background: #fff;
			padding: 3em;
		}

			.box.style1 .image {
				display: block;
				position: absolute;
				top: 0;
				width: 50%;
				height: 100%;
				background: #152E33;
				overflow: hidden;
			}

				.box.style1 .image img {
					position: absolute;
					top: 0;
					height: 100%;
					width: auto;
				}

			.box.style1 .inner > :last-child {
				margin: 0;
			}

			.box.style1.right .image {
				left: 0;
			}

				.box.style1.right .image img {
					right: 0;
				}

			.box.style1.right .inner {
				margin-left: 50%;
				padding-left: 3em;
			}

			.box.style1.left .image {
				right: 0;
			}

				.box.style1.left .image img {
					left: 0;
				}

			.box.style1.left .inner {
				margin-right: 50%;
				padding-right: 3em;
			}

		.box.style2 {
			text-align: center;
		}

			.box.style2 header {
				display: inline-block;
				background: #fff;
				padding: 2em 3em 2em 3em;
				margin: 0;
			}

				.box.style2 header p {
					padding: 0;
				}

			.box.style2 .inner {
				position: relative;
				padding: 40px 0 0px 0;
			}

				.box.style2 .inner:after {
					content: '';
					display: block;
					position: absolute;
					top: 0;
					left: 50%;
					height: 100%;
					border-left: solid 1px #fff;
				}

				.box.style2 .inner .row {
					position: relative;
				}

					.box.style2 .inner .row:before {
						content: '';
						display: block;
						position: absolute;
						top: 50%;
						left: 20px;
						width: calc(100% - 40px);
						border-bottom: solid 1px #fff;
					}

				.box.style2 .inner .image {
					position: relative;
					z-index: 1;
					padding: 20px;
				}

		.box.style3 {
			background: #fff;
			padding: 3em;
		}

			.box.style3 header {
				text-align: center;
			}

/* Icons */

	.icon {
		text-decoration: none;
	}

		.icon:before {
			display: inline-block;
			font-family: FontAwesome;
			font-size: 1.25em;
			text-decoration: none;
			font-style: normal;
			font-weight: normal;
			line-height: 1;
			-webkit-font-smoothing: antialiased;
			-moz-osx-font-smoothing: grayscale;
		}

		.icon > .label {
			display: none;
		}

/* Header */

	#header {
		-moz-transition: opacity 2s ease-in-out;
		-webkit-transition: opacity 2s ease-in-out;
		-ms-transition: opacity 2s ease-in-out;
		transition: opacity 2s ease-in-out;
		position: relative;
		color: #fff;
		text-shadow: 0 0 0.5px rgba(255, 255, 255, 0.25);
		text-align: center;
		margin: 0;
		padding: 14em 0 14em 0;
		cursor: default;
	}

		#header header {
			display: inline-block;
			padding: 0 0 4.5em 0;
		}

			#header header h1 {
				font-weight: 600;
				font-size: 2em;
				letter-spacing: 10px;
			}

			#header header p {
				border-top: solid 1px rgba(255, 255, 255, 0.5);
				color: rgba(255, 255, 255, 0.75);
				text-shadow: 0 0 0.5px rgba(255, 255, 255, 0.1875);
				font-size: 1em;
				text-transform: uppercase;
				letter-spacing: 3px;
				padding: 0;
				margin-top: 0.35em;
			}

				#header header p:before {
					content: '';
					display: block;
					border-top: solid 1px rgba(255, 255, 255, 0.5);
					margin: 4px 0 0.8em 0;
				}

		#header footer {
			-moz-transition: opacity 2s ease-in-out, -moz-transform 1s ease-in-out;
			-webkit-transition: opacity 2s ease-in-out, -webkit-transform 1s ease-in-out;
			-ms-transition: opacity 2s ease-in-out, -ms-transform 1s ease-in-out;
			transition: opacity 2s ease-in-out, transform 1s ease-in-out;
			-moz-transition-delay: 1.25s;
			-webkit-transition-delay: 1.25s;
			-ms-transition-delay: 1.25s;
			transition-delay: 1.25s;
			position: absolute;
			bottom: 9em;
			margin: 0;
			width: 100%;
		}

			#header footer:after {
				content: '';
				display: block;
				position: absolute;
				bottom: -9em;
				left: 50%;
				height: 9em;
				border-left: solid 1px #fff;
			}

			#header footer:before {
				content: '';
				display: block;
				width: 90px;
				height: 66px;
				position: absolute;
				left: 50%;
				bottom: -4.5em;
				margin-left: -45px;
				margin-bottom: -33px;
				background: url("images/arrow.svg") no-repeat;
			}

		body.is-preload #header {
			opacity: 0;
		}

			body.is-preload #header footer {
				-moz-transform: translateY(1em);
				-webkit-transform: translateY(1em);
				-ms-transform: translateY(1em);
				transform: translateY(1em);
				opacity: 0;
			}

/* Banner */

	#banner {
		position: relative;
		color: #fff;
		text-shadow: 0 0 0.5px rgba(255, 255, 255, 0.25);
		text-align: center;
		background: #35b88f url("images/banner.svg") bottom center no-repeat;
		padding: 5em 0 5em 0;
		margin: 0;
		background-size: 125% auto;
	}

		#banner .button {
			color: #35b882;
			text-shadow: 0 0 0.5px rgba(53, 184, 130, 0.25);
		}

		#banner header {
			margin: 0 0 2em 0;
		}

			#banner header h2 {
				font-weight: 400;
				font-size: 1.75em;
				letter-spacing: 8px;
			}

		#banner p {
			margin: 0;
		}

		#banner footer {
			margin: 2em 0 0 0;
		}

		#banner a {
			color: inherit;
			border-bottom-color: rgba(255, 255, 255, 0.5);
		}

			#banner a:hover {
				border-bottom-color: rgba(255, 255, 255, 0);
			}

/* Footer */

	#footer {
		position: relative;
		color: #fff;
		text-shadow: 0 0 0.5px rgba(255, 255, 255, 0.25);
		text-align: center;
		margin: 4.5em 0 0 0;
	}

		#footer:after {
			content: '';
			display: block;
			position: absolute;
			top: -4.5em;
			left: 50%;
			height: 4.5em;
			border-left: solid 1px #fff;
		}

		#footer a {
			color: #fff;
			text-shadow: 0 0 0.5px rgba(255, 255, 255, 0.25);
			border-bottom-color: rgba(255, 255, 255, 0.5);
		}

			#footer a:hover {
				color: #35b88f;
				text-shadow: 0 0 0.5px rgba(69, 200, 159, 0.25);
				border-bottom-color: rgba(53, 184, 143, 0.5);
			}

		#footer .icons {
			padding: 0.75em 2em 0.75em 2em;
			border-radius: 3em;
			border: solid 1px #fff;
			display: inline-block;
			margin: 0 0 3em 0;
		}

		#footer .copyright {
			margin: 0 0 9em 0;
			font-size: 0.8em;
		}

/* Poptrox */

	.poptrox-popup {
		-moz-box-sizing: content-box;
		-webkit-box-sizing: content-box;
		-ms-box-sizing: content-box;
		box-sizing: content-box;
		background: #fff;
		padding-bottom: 3em;
	}

		.poptrox-popup .loader {
			width: 48px;
			height: 48px;
			background: url("images/loader.gif");
			position: absolute;
			top: 50%;
			left: 50%;
			margin: -24px 0 0 -24px;
		}

		.poptrox-popup .caption {
			position: absolute;
			bottom: 0;
			left: 0;
			background: #fff;
			width: 100%;
			height: 3em;
			line-height: 3em;
			text-align: center;
			cursor: default;
			z-index: 1;
		}

		.poptrox-popup .nav-next,
		.poptrox-popup .nav-previous {
			-moz-transition: opacity 0.5s ease-in-out;
			-webkit-transition: opacity 0.5s ease-in-out;
			-ms-transition: opacity 0.5s ease-in-out;
			transition: opacity 0.5s ease-in-out;
			position: absolute;
			top: 0;
			width: 50%;
			height: 100%;
			opacity: 0;
			cursor: pointer;
			background: rgba(0, 0, 0, 0.01);
			-webkit-tap-highlight-color: rgba(255, 255, 255, 0);
		}

			.poptrox-popup .nav-next:before,
			.poptrox-popup .nav-previous:before {
				content: '';
				position: absolute;
				width: 96px;
				height: 64px;
				background: url("images/poptrox-nav.svg");
				top: calc(50% - 1.5em);
				margin: -32px 0 0 0;
			}

		.poptrox-popup:hover .nav-next,
		.poptrox-popup:hover .nav-previous {
			opacity: 0.5;
		}

			.poptrox-popup:hover .nav-next:hover,
			.poptrox-popup:hover .nav-previous:hover {
				opacity: 1.0;
			}

		.poptrox-popup .nav-next {
			right: 0;
		}

			.poptrox-popup .nav-next:before {
				right: 0;
			}

		.poptrox-popup .nav-previous {
			left: 0;
		}

			.poptrox-popup .nav-previous:before {
				-moz-transform: scaleX(-1);
				-webkit-transform: scaleX(-1);
				-ms-transform: scaleX(-1);
				transform: scaleX(-1);
				left: 0;
				-ms-filter: "FlipH";
				filter: FlipH;
			}

		.poptrox-popup .closer {
			-moz-transition: opacity 0.5s ease-in-out;
			-webkit-transition: opacity 0.5s ease-in-out;
			-ms-transition: opacity 0.5s ease-in-out;
			transition: opacity 0.5s ease-in-out;
			position: absolute;
			top: 0;
			right: 0;
			width: 64px;
			height: 64px;
			text-indent: -9999px;
			z-index: 2;
			opacity: 0;
			-webkit-tap-highlight-color: rgba(255, 255, 255, 0);
		}

			.poptrox-popup .closer:before {
				-moz-transition: background-color 0.5s ease-in-out;
				-webkit-transition: background-color 0.5s ease-in-out;
				-ms-transition: background-color 0.5s ease-in-out;
				transition: background-color 0.5s ease-in-out;
				content: '';
				display: block;
				position: absolute;
				right: 16px;
				top: 16px;
				width: 40px;
				height: 40px;
				border-radius: 100%;
				box-shadow: inset 0 0 0 1px #fff;
				background: rgba(255, 255, 255, 0.1) url("images/poptrox-closer.svg") center center;
				color: #fff !important;
			}

		.poptrox-popup:hover .closer {
			opacity: 0.5;
		}

			.poptrox-popup:hover .closer:hover {
				opacity: 1.0;
			}

/* Wide */

	@media screen and (max-width: 1680px) {

		/* Basic */

			body, input, textarea, select {
				font-size: 16pt;
			}

		/* Header */

			#header {
				padding: 10em 0 12em 0;
			}

	}

/* Normal */

	@media screen and (max-width: 1080px) {

		/* Banner */

			#banner {
				padding: 4em 0 4em 0;
				background-size: auto, 175% auto;
			}

		/* Header */

			#header {
				padding: 8em 0 10em 0;
			}

	}

/* Narrow */

	@media screen and (max-width: 840px) {

		/* Basic */

			body {
				background-color: #203936;
				background-image: url("images/overlay.png"), url("../../images/bg-alt.jpg");
				background-repeat: repeat, no-repeat;
				background-size: auto, 100% auto;
				background-position: top left, top center;
				background-attachment: scroll, scroll;
				font-size: 14pt;
			}

			input, textarea, select {
				font-size: 14pt;
			}

			h1, h2, h3, h4, h5, h6 {
				line-height: 1.5em;
			}

			header p {
				margin: 0.25em 0 0 0;
				padding: 0 0 0.5em 0;
			}

		/* Box */

			.box {
				position: relative;
			}

				.box section {
					margin: 0 0 2em 0;
				}

				.box.style1 {
					padding: 2.5em 2em 2.5em 2em;
				}

					.box.style1.right .inner {
						padding-left: 2em;
					}

					.box.style1.left .inner {
						padding-right: 2em;
					}

				.box.style2 header {
					padding: 2em;
				}

				.box.style2 .inner {
					position: relative;
					padding: 30px 0 0 0;
				}

				.box.style3 {
					padding: 2.5em 2em 2.5em 2em;
				}

		/* Header */

			#header {
				padding: 10em 0 12em 0;
			}

		/* Banner */

			#banner {
				padding: 3.5em;
				background-size: 200% auto;
			}

				#banner br {
					display: none;
				}

	}

/* Mobile */

	@media screen and (max-width: 736px) {

		/* Basic */

			* {
				text-shadow: none !important;
			}

			body, input, textarea, select {
				line-height: 1.5em;
				font-size: 12pt;
				letter-spacing: 0;
			}

			h2, h3, h4, h5, h6 {
				font-size: 1em;
			}

			h2 {
				font-size: 1.25em;
				letter-spacing: 4px;
			}

		/* List */

			ul li {
				padding-left: 0.5em;
			}

			ol li {
				padding-left: 0.25em;
			}

		/* Icons */

			ul.icons a {
				width: 2em;
				height: 2em;
				line-height: 2em;
			}

		/* Menu */

			ul.menu li {
				display: block;
				padding: 0;
				border: 0;
				margin: 1em 0 0 0;
			}

				ul.menu li:first-child {
					margin-top: 0;
				}

		/* Actions */

			ul.actions li {
				display: block;
				margin: 1em 0 0 0;
			}

				ul.actions li:first-child {
					margin-top: 0;
				}

		/* Button */

			input[type="button"],
			input[type="submit"],
			input[type="reset"],
			button,
			.button {
				padding: 0.75em 0 0.75em 0;
				width: 100%;
				max-width: 320px;
			}

		/* Box */

			.box {
				margin-top: 4.5em;
			}

				.box:after {
					top: -4.5em;
					height: 4.5em;
				}

				.box:before {
					width: 45px;
					height: 33px;
					top: -2.25em;
					margin-left: -22.5px;
					margin-top: -16.5px;
					background-size: 45px 33px;
				}

				.box.style1 {
					padding: 0;
					text-align: center;
				}

					.box.style1 .image {
						position: relative !important;
						left: 0 !important;
						width: 100% !important;
						height: auto !important;
					}

						.box.style1 .image img {
							position: relative;
							height: auto;
							width: 100%;
						}

					.box.style1 .inner {
						margin: 0 !important;
						padding: 2em 1.25em 2em 1.25em !important;
					}

				.box.style2 .inner .row:before {
					display: none;
				}

				.box.style2 .inner .image {
					padding: 0;
					max-width: 250px;
					margin: 0 auto 20px auto;
				}

				.box.style3 {
					padding: 2em 1.25em 2em 1.25em;
				}

		/* Header */

			#header {
				padding: 6em 0 6em 0;
			}

				#header header {
					padding-left: 2em;
					padding-right: 2em;
				}

					#header header h1 {
						font-size: 1.75em;
						letter-spacing: 6px;
					}

				#header footer {
					bottom: 4.5em;
					padding: 0 2em 0 2em;
				}

					#header footer:after {
						bottom: -4.5em;
						left: 50%;
						height: 4.5em;
					}

					#header footer:before {
						width: 45px;
						height: 33px;
						bottom: -2.25em;
						margin-left: -22.5px;
						margin-bottom: -16.5px;
						background-size: 45px 33px;
					}

		/* Banner */

			#banner {
				padding: 3em 2em 3em 2em;
				background-size: auto 150%;
			}

				#banner header {
					margin: 0 0 1em 0;
				}

					#banner header h2 {
						font-size: 1.5em;
						letter-spacing: 6px;
					}

		/* Footer */

			#footer .icons {
				padding: 0.5em 1.25em 0.5em 1.25em;
			}

			#footer .copyright {
				font-size: 1em;
				margin: 0 0 4em 0;
			}

		/* Poptrox */

			.poptrox-popup .nav-next,
			.poptrox-popup .nav-previous {
				opacity: 1.0;
			}

				.poptrox-popup .nav-next:before,
				.poptrox-popup .nav-previous:before {
					display: none;
				}

			.poptrox-popup .closer {
				opacity: 0.5;
			}

	}
