<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Laboratorios Fundamentos de Ciberseguridad DOJO 2024</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-transparentGray { background-color: rgba(227, 226, 224, 0); }
.select-value-color-translucentGray { background-color: rgba(0, 0, 0, 0.06); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="8446adaa-b828-460b-8c07-2a6fe4b5d568" class="page sans"><header><img class="page-cover-image" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/ZoomBG_Fundamentos2024.png" style="object-position:center 93.11%"/><h1 class="page-title">Laboratorios Fundamentos de Ciberseguridad DOJO 2024</h1><p class="page-description"></p></header><div class="page-body"><p id="150aca47-0e93-475b-86bd-d2b56de8c87b" class="">
</p><h3 id="037ee313-4edc-42fd-80f7-1d4656e3f33b" class=""><mark class="highlight-yellow"><strong>Lab #1</strong></mark><mark class="highlight-yellow"> </mark>Virtualización</h3><figure id="a886ac85-93ff-4deb-abf1-363cee04c256" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled.png"><img style="width:842px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled.png"/></a></figure><p id="3b51e27c-4c35-43e3-a4f1-f3b1d407fce7" class="">
</p><hr id="b369a898-6813-4d9f-a19c-5dad8db33eb7"/><h3 id="1548e5c6-e5e7-478b-a8b5-95da6f6957c2" class=""><mark class="highlight-yellow">Lab #2</mark> Pfsense</h3><figure id="a71c10ab-a486-409d-9dc9-fa2a51a82a0c" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/pfsense_1.png"><img style="width:1355px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/pfsense_1.png"/></a></figure><p id="121f749c-b253-4917-bfec-a3876aa6f746" class="">
</p><figure id="7f82531d-3076-413e-ad51-042c9e3eeaca" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/pfsense_terminado.png"><img style="width:720px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/pfsense_terminado.png"/></a></figure><hr id="f6b9948a-a7fe-4740-8fb2-9b73e0d6130d"/><h3 id="5a02afde-2392-422e-8741-e58888ae0a82" class=""><mark class="highlight-yellow">Lab #3</mark> <em>Introducción a Linux y comandos fundamentales</em></h3><p id="b88696f1-92ee-4737-a91c-85117efa5399" class="">
</p><p id="34130dde-d6ce-4047-ab7b-d38eb1dec7a4" class=""><strong><span style="border-bottom:0.05em solid">Bandit</span></strong></p><figure id="653a08e4-726e-4a97-8b7a-156cefaaab33" class="image" style="text-align:left"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%201.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%201.png"/></a></figure><p id="dc5b58fb-bd59-4e1b-875e-a2c8aea268c4" class="">
</p><p id="7096fef8-d7ea-4ed5-9809-5ceb17973e32" class=""><strong>Level0→Level1</strong><div class="indented"><figure id="9675741b-b463-4b3c-9b37-d1b68423687d" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/67d6231b-4384-4bec-8580-ff58fed50fca.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/67d6231b-4384-4bec-8580-ff58fed50fca.png"/></a></figure></div></p><p id="be0d2caa-7d1c-4fac-8da9-696bc330bc22" class=""><strong>Level1→Level2</strong><div class="indented"><figure id="51bb790a-48d8-4326-ae56-052efd712a38" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%202.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%202.png"/></a></figure></div></p><p id="79088c41-6d9e-4c35-8bc3-8d645ca12852" class=""><strong>Level2→Level3</strong><div class="indented"><figure id="e0090a48-454e-45be-b1f0-0b678e619b53" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%203.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%203.png"/></a></figure></div></p><p id="17b10c2d-21de-4358-9884-117fb2bb5298" class=""><strong>Level3→Level4</strong><div class="indented"><figure id="d2f130ce-b69f-48ff-aa4b-61e155cfe4d0" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%204.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%204.png"/></a></figure></div></p><p id="a1a407d7-2d58-4d12-9175-fddecd88aaa1" class=""><strong>Level4→Level5</strong><div class="indented"><figure id="9f55cc08-95ec-4f33-ac3f-cfb0935cc016" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%205.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%205.png"/></a></figure></div></p><p id="1e0bebc0-9450-48e4-83f0-6a4dcec8f546" class=""><strong>Level5→Level6</strong><div class="indented"><figure id="365716ce-231e-46d9-a766-11665c14effc" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%206.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%206.png"/></a></figure></div></p><p id="13c2e11f-b02c-410c-8467-0056e1692ed1" class=""><strong>Level6→Level7</strong><div class="indented"><figure id="f7f0d7b7-8c1c-4e1d-bb10-205334037dbe" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%207.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%207.png"/></a></figure></div></p><p id="924e28cc-a3b0-4e66-94f0-387cf7cf42d1" class=""><strong>Level7→Level8</strong><div class="indented"><figure id="eb06e036-7190-4ec7-a5d4-cdd3660abc59" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%208.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%208.png"/></a></figure></div></p><p id="ae3ee2d8-99a3-4881-9529-f9f8c7f9eb64" class=""><strong>Level8→Level9</strong><div class="indented"><figure id="36df4bf5-65fc-4f87-a015-6c575a2ba6db" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%209.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%209.png"/></a></figure></div></p><p id="bfadd324-3952-46c1-b0dc-c5b59c0a0110" class=""><strong>Level9→Level10</strong><div class="indented"><figure id="8cf6bb38-73aa-408a-ad7d-ef43a9d870ec" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2010.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2010.png"/></a></figure></div></p><p id="df75d3d1-79bf-431c-b29e-2e293f841285" class=""><strong>Level10</strong><div class="indented"><figure id="ac87e6e3-8c41-4520-84ff-87484042fadf" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2011.png"><img style="width:576px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2011.png"/></a></figure></div></p><p id="b0591dc6-ec5f-4222-9c2b-2519f3e02a5a" class="">
</p><p id="323c10eb-ef57-45fc-b514-c1147746aa51" class=""><strong><span style="border-bottom:0.05em solid">CMD challenge</span></strong><div class="indented"><figure id="41ee120f-b3f2-4197-8eff-db48500dea07" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2012.png"><img style="width:680px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2012.png"/></a></figure></div></p><p id="d171afa8-1cdd-4d42-a1d2-dd76e0a9970f" class="">
</p><hr id="b4f1a496-7143-4eb5-85a0-f9459e6d2d93"/><h3 id="36f1a74b-3213-4024-97d2-04f89a10f273" class=""><mark class="highlight-yellow">Lab #4  </mark><em>Keycloak y Cifrado con Kleopatra</em></h3><h3 id="c764fb3f-d24d-47b4-8b4e-c4feb748173f" class=""><strong>Keycloak </strong></h3><figure id="04e9195b-e80b-4183-9138-c6bd0511095e" class="image" style="text-align:left"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/keycloak_p1.png"><img style="width:528px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/keycloak_p1.png"/></a></figure><p id="a338c835-68eb-4c68-bb26-85aa3cadcf6c" class="">
</p><ul id="8d4a7100-adf2-48ad-8b8f-ec9f0fdf95a6" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked"><mark class="highlight-brown_background"><strong>Creación de los usuarios</strong></mark></span><div class="indented"></div></li></ul><figure id="7ac5538a-aa9f-4e49-b636-5739c4c236de" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/keycloak_users.png"><img style="width:963px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/keycloak_users.png"/></a></figure><ul id="255b79d3-7ca4-4773-9612-e8702730efc1" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked"><mark class="highlight-brown_background"><strong>Creación del grupo</strong></mark></span><div class="indented"></div></li></ul><figure id="b8697b62-5ba1-4f72-9697-ccdc24612b2e" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/keycloak_group.png"><img style="width:1007px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/keycloak_group.png"/></a></figure><ul id="f41c3566-ad43-4157-9ba5-4e8493991e64" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked"><mark class="highlight-brown_background"><strong>Creación del rol</strong></mark></span><div class="indented"></div></li></ul><figure id="f78302dc-040f-4833-b28c-37ced62aa7d6" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/creando_un_rol_keycloak.png"><img style="width:893px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/creando_un_rol_keycloak.png"/></a></figure><ul id="a5e10a04-df08-4a93-ac98-1a0c94180fa0" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked"><mark class="highlight-brown_background"><strong>Agregando a los usuarios al grupo</strong></mark></span><div class="indented"></div></li></ul><figure id="d292f465-2ec7-470a-a9d3-0499a16f0013" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/keycloak_group%201.png"><img style="width:1007px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/keycloak_group%201.png"/></a></figure><ul id="293a0612-01ef-40d2-ba01-85364c8ccdf9" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked"><mark class="highlight-brown_background"><strong>Asignación de un rol al grupo para los 3 usuarios</strong></mark></span><div class="indented"></div></li></ul><figure id="7aab2f2a-6d28-4144-8bc2-f40f1ba608a8" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/rol_asignado_al_grupo_keycloak.png"><img style="width:984px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/rol_asignado_al_grupo_keycloak.png"/></a></figure><ul id="88e38cf0-f901-4868-b08e-97689da75b12" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked"><mark class="highlight-brown_background"><strong>Activando el MFA de la cuenta admin</strong></mark></span><div class="indented"></div></li></ul><figure id="fb674a35-e51a-4404-96e5-42b04e85a12d" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/autentificacion_keycloak.png"><img style="width:953px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/autentificacion_keycloak.png"/></a></figure><p id="755ee50c-3845-4b00-94ec-4d3db080f1ab" class="">
</p><h3 id="3369952b-204a-4a1f-bd11-37a8dbb10b02" class=""><em>Cifrado con Kleopatra</em></h3><p id="73ac2973-b845-47e4-ad4f-bb9056dea064" class="">
</p><ul id="c7a774b8-f23a-44dc-9d82-21dd7a0e8872" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked">Kleopatra instalado y funcionando</span><div class="indented"></div></li></ul><figure id="30bc66af-5691-46a2-9d62-200148852f9e" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2013.png"><img style="width:1035px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2013.png"/></a></figure><ul id="34b71321-53ff-42c8-aabd-ef4f5c488a04" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked">Creación del archivo para utilizar en kleopatra</span><div class="indented"></div></li></ul><figure id="d2ac8bbb-a8a0-47ff-911f-b2ddb128e332" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2014.png"><img style="width:1049px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2014.png"/></a></figure><ul id="5edd9090-5193-4cf9-9b71-1a434874510d" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked">Eliminación del texto plano en .txt</span><div class="indented"></div></li></ul><figure id="3f9e5810-e372-4224-9811-fd71a8182f39" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2015.png"><img style="width:969px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2015.png"/></a></figure><ul id="d6616761-027b-468f-b1ab-ff7120633bd3" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked">Mensaje encriptado</span><div class="indented"></div></li></ul><figure id="f443120c-2246-426b-976e-9fbdf36f05c0" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2016.png"><img style="width:966px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2016.png"/></a></figure><ul id="5895ca21-37c5-4952-b1f3-4b727624ad7e" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked">Descifrado del mensaje</span><div class="indented"></div></li></ul><figure id="c9f9f42e-a031-40b2-a492-0abe6254522a" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2017.png"><img style="width:1015px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2017.png"/></a></figure><hr id="35ebea11-12f4-4932-860d-2513ab5e9017"/><h3 id="b5bddb34-5566-4251-ac64-863fd0f6dacd" class=""><mark class="highlight-yellow">Lab #5  </mark><em>Laboratorio OSINT</em></h3><p id="fe2ad65e-9126-486a-808a-8236e7c7e417" class="">
</p><ul id="c6fe5804-7426-4e8e-a701-1ab05fe78556" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked">Reconocimiento con Exiftool</span><div class="indented"></div></li></ul><figure id="9dc1cfd4-13d4-4a3e-876b-865bd9571f6c" class="image" style="text-align:left"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2018.png"><img style="width:599px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2018.png"/></a></figure><ul id="aaee6305-b5da-482a-944c-5ccf1cab0208" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked">Localización del imagen por medio de streetview</span><div class="indented"></div></li></ul><figure id="608789c0-fd64-44f7-9325-f85371f0449e" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2019.png"><img style="width:1046px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2019.png"/></a></figure><figure id="2655e924-8361-4e12-8c83-67e25301dd85" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2020.png"><img style="width:988px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2020.png"/></a></figure><hr id="fe4c3b0e-0325-446c-95b8-ae23de0f1b50"/><h3 id="6c92721a-b39c-4b4d-8a34-b4fc0b1bb6c4" class="">Reconocimiento y análisis del dominio comunidaddojo.org</h3><ul id="5a85eb4d-1980-45fa-8894-31cdc01abd58" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked">Nombre del dominio</span><div class="indented"></div></li></ul><figure id="dbf49585-b62a-4da9-88bf-7e6c919539c7" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2021.png"><img style="width:930px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2021.png"/></a></figure><ul id="5804f5cd-7f61-42d8-9ae6-08f45a2e67a8" class="to-do-list"><li><div class="checkbox checkbox-on"></div> <span class="to-do-children-checked">subdominios</span><div class="indented"></div></li></ul><figure id="04ff2d95-40a3-49ac-bd34-bd0ef692d4f5" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2022.png"><img style="width:1158px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2022.png"/></a></figure><p id="40a611be-045e-443e-8666-bf399411ac65" class=""><strong>DNS servers, direcciones ip, proveedores de los servidores DNS y de correo electrónico de<br/>Comunidad Dojo.<br/></strong></p><figure id="a0374b84-3a8a-4727-a8b3-cc56b0673c48" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2023.png"><img style="width:804px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2023.png"/></a></figure><figure id="06dc22d5-09cb-4edc-b0e5-3ef5ce8a5936" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2024.png"><img style="width:708px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/Untitled%2024.png"/></a></figure><p id="07465332-cfdd-41fd-9c78-3fb653e5c54c" class=""><em>Herramienta dnsdumpster</em></p><hr id="5c7b3164-650b-42cb-a2d4-a1c4f8c7ee27"/><h3 id="77521f0e-5ca3-4ad0-8369-29c60227cd89" class="">Utilización de Shodan</h3><p id="00427e13-e816-481b-bdd4-caf407bc8d59" class="">Captura de pantalla donde se muestre la dirección IP, geolocalización y los puertos abiertos en mi país y mi ciudad.</p><figure id="8d331af7-b8d8-4076-880f-02216ec68820" class="image"><a href="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/country_PA_city_Panam_-_Shodan_Search-1.png"><img style="width:708px" src="Laboratorios%20Fundamentos%20de%20Ciberseguridad%20DOJO%2020%208446adaab828460b8c072a6fe4b5d568/country_PA_city_Panam_-_Shodan_Search-1.png"/></a></figure></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
