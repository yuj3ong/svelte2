<style>
	.body {
		flex-direction: column;
		justify-content: flex-start;
		position: relative;
		width: 100%;
		/* height: 900px; */

		text-align: center;
		padding-top: 100px;
		display: flex;
	}

	.center {
		flex-wrap: wrap;
		align-content: flex-start;
		height: 100px;
	}

	.center-text1 {
		align-self: flex-end;
		left: 1;
		top: 110px;
		width: 100%;
		text-align: center;
		font-size: 45px;
		color: red;
	}

	.center-text2 {
		align-self: flex-start;
		left: 0;
		top: 50px;
		width: 100%;
		text-align: center;
		font-size: 24px;
	}

	.top-bubble {
		position: absolute;
		left: 0;
		top: 0;
		width: 100%;
		text-align: left;
	}

	.bottom-map {
		text-align: left;
		margin-left: 10px;
	}

	dl dt {
		display: inline-block;
	}

	dl dd {
		display: inline-block;
		float: none;
		margin-left: 10px;
	}

	.top-bubble .floating-text-top {
		position: absolute;
		top: 10px;
		background: red;
		text-align: center;
		width: 100%;
	}

	.top-bubble .floating-text-top strong {
		color: yellow;
	}

	.title-area {
		position: absolute;
		top: 200px;
		left: 0;
		width: 100%;
	}

	.title-area h1 {
		padding-left: 100px;
		display: inline-block;
	}
	.title-area p {
		position: absolute;
		left: 0;
		top: 0;
		width: 100%;
		margin-left: -60px;
	}

	.center-bubble {
		padding-top: 50px;
		display: inline-flex;
		align-items: center;
		justify-content: center;
	}

	.center-bubble strong {
		font-weight: bold;
	}

	.center-bubble p strong {
		color: red;
	}

	.bottom-map {
		margin-top: 100px;
		background: blue;
		padding: 20px;
	}

	.bottom-map > dl {
		background: red;
	}
	.bottom-map > dl > dt {
		display: inline-block;
		vertical-align: top;
	}
	.bottom-map > dl > dd {
		display: inline-block;
	}
	.bottom-map > dl > dd > dl {
		display: block;
	}

	address {
		font-style: normal;
	}
	address dl dt {
		color: yellow;
	}
	address dl dd {
		color: white;
	}
</style>

<script>
	import Header from '../../components/header/Header.svelte';
</script>

<div>
	<Header />

	<div> html1 </div>

	<head>
		<title>도그버디</title>
	</head>

	<div class="body">
		<div class="title-area">
			<h1><strong>도그버디</strong></h1>
			<p><span>애견용품 할인매장</span></p>
		</div>

		<div class="center">
			<p>
				<strong class="center-text1"> GRAND OPEN </strong>
				<span class="center-text2">2016.11.06(일)</span>
			</p>
		</div>

		<div class="top-bubble">
			<p class="floating-text-top">전단지 지참시 모든 품목 <strong>10% 할인</strong></p>
		</div>

		<div class="center-bubble">
			<p
				>내 반려견의 편안한 안식처, 애견용품 할인매장 도그버디가<br /><strong
					>여러분과 함께합니다!</strong
				></p
			>
		</div>
		<!-- <dl>
		<dt>영업시간</dt>
		<dt>평일</dt>
		<dd>AM10:00~PM10:00</dd>
		<dt>주말</dt>
		<dd>AM10:00~PM8:00</dd>
	</dl> -->
		<div class="bottom-map">
			<dl>
				<dt>영업시간</dt>
				<dd>
					<dl>
						<dt>평일</dt>
						<dd>AM10:00~PM10:00</dd>
					</dl>
					<dl>
						<dt>주말</dt>
						<dd>AM10:00~PM8:00</dd>
					</dl>
				</dd>
			</dl>

			<address>
				<dl>
					<dt> 문의 </dt>
					<dd> 070-4266-9323</dd>
				</dl>
			</address>
		</div>
	</div>
</div>

<!-- <div>
			<img src="../../../public/vite.svg" />
		</div> -->
