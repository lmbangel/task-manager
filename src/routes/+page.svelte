<div class="card card-flush">
	<div class="card-header pt-8">
		<div class="mr-auto" id="new-task">
			<a href="" class="btn border border-0 py-2 px-10" type="button"> New Task</a>
		</div>
	</div>
	<div class="card-body">
		<div class="row">
			<div
				id="sales-data"
				style="overflow-x:scroll;  border-collapse: collapse;border-spacing: 0;width: 100%;"
			>
				<table class="table table-hover responsive no-wrap" id="sales-data-table">
					<thead class="border-bottom">
						<tr>
							<th>Task</th>
							<th>Description</th>
							<th>Owner</th>
							<th>Status</th>
							<th>Priority</th>
							<th>Type</th>
							<th>Role</th>
							<th>Due Date</th>
							<th />
						</tr>
					</thead>
					<tbody />
				</table>
			</div>
		</div>
	</div>
</div>

<style>
	#new-task > .btn {
		color: #093c71;
		font-weight: 500;
		background-color: rgba(9, 43, 113, 0.1);
	}

	#new-task > .btn:hover {
		text-decoration: underline !important;
		color: #fff;
		background-color: rgba(9, 43, 113, 1);
	}
</style>
