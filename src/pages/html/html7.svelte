<style>
	.viewer {
		display: flex;
		flex-direction: column;
	}

	.head,
	.body,
	.footer {
		display: flex;
	}

	.head {
		justify-content: space-between;
	}

	.topButton {
		display: flex;
	}

	.topButton ul {
		display: flex;
		flex-direction: row;
		justify-content: flex-start;
	}

	.icon {
		/* background: url(../../../public/top1.png) no-repeat 100%; */
		border: 1px solid black;
		width: 36px;
		height: 36px;
	}

	.topTimetable {
		display: flex;
	}

	.btnBundle + .btnBundle {
		margin-left: 20px;
		border-left: 3px solid pink;
	}

	.btnBundle li + li {
		margin-left: 10px;
	}
	.icon1 {
		background: red;
		width: 100%;
	}

	/*  */

	.sideTab {
		display: flex;
		flex-direction: column;
	}

	.hostTab {
		display: flex;
	}

	.hostTab ul {
		display: flex;
	}

	.hostTab ul li + li {
		display: flex;
		margin-left: 5px;
	}

	.treeIcon {
		display: flex;
	}

	.treeIcon ul {
		display: flex;
		flex-direction: row;
	}

	.btnBundle2 + .btnBundle2 {
		margin-left: 5px;
		border-left: 3px solid pink;
	}

	.treeCon {
		/* background: url(../../../public/top1.png) no-repeat 100%; */
		border: 1px solid black;
		width: 25px;
		height: 25px;
	}

	.tree1 {
		background: red;
		width: 100%;
	}
</style>

<main>
	<div class="viewer">
		<!-- <head>, <body>, <footer> stack -->
		<div class="head">
			<!--  -->
			<div class="topButton">
				<ul>
					<li class="btnBundle">
						<ul>
							<li class="icon">
								<button class="icon1">icon1</button>
							</li>
							<li class="icon">
								<button class="icon2">icon2</button>
							</li>
						</ul>
					</li>

					<li class="btnBundle">
						<ul>
							<li class="icon">
								<button class="icon3">icon3</button>
							</li>
							<li class="icon">
								<button class="icon4">icon4</button>
							</li>
						</ul>
					</li>

					<li class="btnBundle">
						<ul>
							<li class="icon">
								<button class="icon5">icon5</button>
							</li>
							<li class="icon">
								<button class="icon6">icon6</button>
							</li>
							<li class="icon">
								<button class="icon7">icon7</button>
							</li>
						</ul>
					</li>

					<li class="btnBundle">
						<ul>
							<li class="icon">
								<button class="icon8">icon8 </button>
							</li>
							<li class="icon">
								<button class="icon8-2">icon8-2</button>
							</li>
							<li class="icon">
								<button class="icon9">icon9</button>
							</li>
							<li class="icon">
								<button class="icon10">icon10</button>
							</li>
							<li class="icon">
								<button class="icon11">icon11</button>
							</li>
						</ul>
					</li>

					<li class="btnBundle">
						<ul>
							<li class="icon">
								<button class="icon12">icon12</button>
							</li>
						</ul>
					</li>
				</ul>
			</div>
			<!--  -->
			<div class="topTimetable">
				<div class="topRealtime">
					<p>Realtime:2023-02-28 17:20:25</p>
				</div>
				<div class="topClock">
					<button class="top-right0">top-right0</button>
				</div>
			</div>
		</div>
		<!--  -->
		<div class="body">
			<div class="sideTab">
				<div class="hostTab">
					<ul>
						<li>host</li>
						<!-- save -->
						<li>groups</li>
						<li>VMWares</li>
						<li>VMWareGroups</li>
						<li>Xens</li>
					</ul>
				</div>
				<div class="treeIcon">
					<ul>
						<li class="btnBundle2">
							<ul>
								<li class="treeCon">
									<button class="tree1">tree1</button>
								</li>
								<li class="treeCon">
									<button class="tree2">tree2</button>
								</li>
							</ul>
						</li>

						<li class="btnBundle2">
							<ul>
								<li class="treeCon">
									<button class="tree3">tree3</button>
								</li>
								<li class="treeCon">
									<button class="tree4">tree4</button>
								</li>
								<li class="treeCon">
									<button class="tree5">tree5</button>
								</li>
							</ul>
						</li>
					</ul>
				</div>
				<div class="hostTree"></div>
			</div>

			<div class="chartTab"></div>
		</div>
		<!--  -->
		<div class="footer">
			<div class="hostCount">
				<p>57 host(s) Selected</p>
			</div>
			<div class="connectOn">
				<p><span>bottomIcon1</span>50</p>
			</div>
			<div class="connectOff">
				<p><span>bottomIcon2</span>27</p>
			</div>
			<div class="bottomRealtime">
				<p><span>bottomIcon3</span>2023-02-28 17:20:25</p>
			</div>
		</div>
		<!--  -->
	</div>
</main>
