```js
if (1 || this.data.checked.length) {
	wx.navigateTo({
		url: `/pages/map/marker/marker?checked=${JSON.stringify(
			this.data.checked
		)}`,
	});
}
```