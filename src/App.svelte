<script>
	import "nes.css/css/nes.min.css";
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<h2>南臺科技大學</h2>
	<p>
		Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
		how to build Svelte apps.
	</p>
	<div class="nes-container with-title ">
		<p style="font-size:x-large" class="title">校訓</p>
		<p>
			南臺科技大學的校訓是在約40年前(1969年)由首任校長辛文炳先生制定。當時南臺剛成立，全名是私立南臺工業實用技藝專科學校。
			校長文炳先生與吳修齊、吳尊賢、張麗堂…等先生同是學校的創辦人。他在南臺當了20年的校長(1969~1989)，10年的董事長(1989~1999)，於南臺任職的30年間文炳先生不但未領分毫薪水、不設工友值役，很多公務上的花費還自掏腰包，甚至捐獻現在的師生活動中心─文炳館與西淮紀念館，是令人懷念敬重的一位長者。
		</p>
	</div>
	<br />
	<div style="text-align:left">
		<section class="message-list">
			<section class="message -left">
				<!-- Balloon -->
				<div class="nes-balloon from-left">
					<p>
						分支機構代碼一覽表 最近一次更新時間:2022-05-15 06:30:14
						sucess
					</p>
					<div style="text-align:left" class="nes-field">
						<label for="name_field">搜尋銀行</label>
						<input type="text" id="name_field" class="nes-input" />
						<div style="text-align:right;margin-top:10px">
							<button class="nes-btn is-primary">查詢</button>
						</div>
					</div>
				</div>
			</section>
		</section>
	</div>
	<div class="nes-table-responsive">
		<table style="width:99%" class="nes-table is-bordered is-centered">
			<thead>
				<tr style="background-color:lightgrey">
					<th>分支機構代碼</th>
					<th>銀行名稱</th>
					<th>分支機構名稱</th>
					<th>簡稱</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>0040037</td>
					<td>臺灣銀行</td>
					<td>營業部</td>
					<td>臺銀營業部</td>
				</tr>
				<tr>
					<td>0040038</td>
					<td>臺灣銀行</td>
					<td>公庫部</td>
					<td>臺銀公庫部</td>
				</tr>
			</tbody>
		</table>
	</div>
	<div style="margin-top:10px">
		<button style="width:100px" class="nes-btn is-primary">確定</button>
		<button style="width:100px" class="nes-btn is-warning">取消</button>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
