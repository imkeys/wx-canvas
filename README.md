# 生成分享卡片

#### 数据配置
<pre>
{
	model: 'block',
	type: 'rect',
	position: {
		x: 0,
		y: 0,
		w: 300,
		h: 440
	},
	backgrondColor: '#18bae8'
},
{
	model: 'crop',
	clipper: {
		type: 'arc',
		position: {
			x: 35,
			y: 35,
			r: 20,
			sAngle: 0,
			eAngle: 2 * Math.PI
		}
	},
	handle: {
		imgurl: that.data.userInfo.avatarUrl,
		position: {
			x: 15,
			y: 15,
			w: 40,
			h: 40
		}
	}
},
{
	model: 'text',
	content: '破解失眠 蝶变重生',
	position: {
		x: 290,
		y: 35
	},
	textAlign: 'right',
	fontSize: '16',
	fontColor: '#ffffff'
},
{
	model: 'image',
	imgurl: '/sources/cover.jpg',
	position: {
		x: 0,
		y: 70,
		w: 300,
		h: 190
	}
}
</pre>
