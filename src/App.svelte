<style>
div {
	border: 1px solid red;
	height: 100px;
	display: flex;
	align-items: center;
	justify-content: center;
	overflow: hidden;
	resize: horizontal;
}
.div1 { width: 100px; }
.div2 { width: 200px; }
.div3 { width: 300px; }
</style>
<input bind:value="{text}">
<div class="div1"><TextFit>{text}</TextFit></div>
<div class="div2"><TextFit>{text}</TextFit></div>
<div class="div3"><TextFit>{text}</TextFit></div>


<script>
import TextFit from './TextFit';
let text = 'My Lovely Text';
</script>
