Osekkai
=======

[![Build Status][travis-img]][travis-url]
[![Coverage Status][coveralls-img]][coveralls-url]
[![Greenkeeper badge](https://badges.greenkeeper.io/hakatashi/osekkai.svg)](https://greenkeeper.io/)

[travis-img]: https://travis-ci.org/hakatashi/osekkai.svg?branch=master
[travis-url]: https://travis-ci.org/hakatashi/osekkai
[coveralls-img]: https://coveralls.io/repos/hakatashi/osekkai/badge.svg?branch=master&service=github
[coveralls-url]: https://coveralls.io/github/hakatashi/osekkai?branch=master

日本語平文を組版に合わせて最適化する、日本語出版史上最強のお節介(予定)

## 理想

```
input: "199X年、世界は核の炎に包まれた!"

json: [
	{
		type: "upright",
		text: "1",
		original: "1"
	},
	{
		type: "upright",
		text: "9",
		original: "9"
	},
	{
		type: "upright",
		text: "9",
		original: "9"
	},
	{
		type: "upright",
		text: "X",
		original: "X"
	},
	{
		type: "plain",
		text: "年、世界は核の炎に包まれた"
	},
	{
		type: "upright",
		text: "!",
		original: "!"
	},
	{
		type: "margin",
		value: "full",
		original: ""
	}
]

plain: １９９Ｘ年、世界は核の炎に包まれた！　
```
