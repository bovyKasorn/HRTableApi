---


---

<h1 id="hrtable-api-documentation">HRTable Api Documentation</h1>
<h3 id="leave-request-list">Leave request list</h3>
<h5 id="request-object-example">Request object example</h5>
<pre class=" language-javascript"><code class="prism  language-javascript">	<span class="token punctuation">{</span>
		URL<span class="token punctuation">:</span> <span class="token string">'https://cloud.hrtable.com/api/v1/admin/leave/list'</span><span class="token punctuation">,</span>
		method<span class="token punctuation">:</span> <span class="token string">'POST'</span><span class="token punctuation">,</span>
		data<span class="token punctuation">:</span> <span class="token punctuation">{</span>
			status<span class="token punctuation">:</span> <span class="token string">'pending'</span><span class="token punctuation">,</span> <span class="token comment">//all, pending, approved, rejected</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>
</code></pre>
<h5 id="response-object-sample">Response object sample</h5>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">//ย้อนหลัง 30 วัน อ้างอิงจาก created_at</span>
	<span class="token punctuation">{</span>
		success<span class="token punctuation">:</span> <span class="token boolean">true</span><span class="token punctuation">,</span>
		response<span class="token punctuation">:</span> <span class="token punctuation">{</span>
			lists<span class="token punctuation">:</span> <span class="token punctuation">[</span>
				<span class="token punctuation">{</span>
					id<span class="token punctuation">:</span> <span class="token number">0</span>
					name<span class="token punctuation">:</span> <span class="token string">'fullname'</span><span class="token punctuation">,</span>
					designation<span class="token punctuation">:</span> <span class="token string">'Sale'</span><span class="token punctuation">,</span>
					leave_type<span class="token punctuation">:</span> <span class="token string">'Leave'</span><span class="token punctuation">,</span>
					avatar<span class="token punctuation">:</span>	<span class="token string">'url'</span> <span class="token comment">// url image profile</span>
				<span class="token punctuation">}</span>
			<span class="token punctuation">]</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>
</code></pre>
<h3 id="expense-request-list">Expense request list</h3>
<h5 id="request-object-example-1">Request object example</h5>
<pre class=" language-javascript"><code class="prism  language-javascript">	<span class="token punctuation">{</span>
		URL<span class="token punctuation">:</span> <span class="token string">'https://cloud.hrtable.com/api/v1/admin/expense/list'</span><span class="token punctuation">,</span>
		method<span class="token punctuation">:</span> <span class="token string">'POST'</span><span class="token punctuation">,</span>
		data<span class="token punctuation">:</span> <span class="token punctuation">{</span>
			status<span class="token punctuation">:</span> <span class="token string">'pending'</span><span class="token punctuation">,</span> <span class="token comment">//all, pending, approved, rejected</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>

</code></pre>
<h5 id="response-object-sample-1">Response object sample</h5>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">//ย้อนหลัง 30 วัน อ้างอิงจาก created_at</span>
	<span class="token punctuation">{</span>
		success<span class="token punctuation">:</span> <span class="token boolean">true</span><span class="token punctuation">,</span>
		response<span class="token punctuation">:</span> <span class="token punctuation">{</span>
			lists<span class="token punctuation">:</span> <span class="token punctuation">[</span>
				<span class="token punctuation">{</span>
					id<span class="token punctuation">:</span> <span class="token number">0</span>
					name<span class="token punctuation">:</span> <span class="token string">'fullname'</span><span class="token punctuation">,</span>
					designation<span class="token punctuation">:</span> <span class="token string">'Sale'</span><span class="token punctuation">,</span>
					expense_type<span class="token punctuation">:</span> <span class="token string">'ค่าเดินทาง'</span><span class="token punctuation">,</span>
					avatar<span class="token punctuation">:</span>	<span class="token string">'url'</span> <span class="token comment">// url image profile</span>
				<span class="token punctuation">}</span>
			<span class="token punctuation">]</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>
</code></pre>
<h3 id="fieldwork-request-list">Fieldwork request list</h3>
<h5 id="request-object-example-2">Request object example</h5>
<pre class=" language-javascript"><code class="prism  language-javascript">	<span class="token punctuation">{</span>
		URL<span class="token punctuation">:</span> <span class="token string">'https://cloud.hrtable.com/api/v1/admin/fieldwork/list'</span><span class="token punctuation">,</span>
		method<span class="token punctuation">:</span> <span class="token string">'POST'</span><span class="token punctuation">,</span>
		data<span class="token punctuation">:</span> <span class="token punctuation">{</span>
			status<span class="token punctuation">:</span> <span class="token string">'pending'</span><span class="token punctuation">,</span> <span class="token comment">//all, pending, approved, rejected</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>

</code></pre>
<h5 id="response-object-sample-2">Response object sample</h5>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">//ย้อนหลัง 30 วัน อ้างอิงจาก created_at</span>
	<span class="token punctuation">{</span>
		success<span class="token punctuation">:</span> <span class="token boolean">true</span><span class="token punctuation">,</span>
		response<span class="token punctuation">:</span> <span class="token punctuation">{</span>
			lists<span class="token punctuation">:</span> <span class="token punctuation">[</span>
				<span class="token punctuation">{</span>
					id<span class="token punctuation">:</span> <span class="token number">0</span>
					name<span class="token punctuation">:</span> <span class="token string">'fullname'</span><span class="token punctuation">,</span>
					designation<span class="token punctuation">:</span> <span class="token string">'Sale'</span><span class="token punctuation">,</span>
					location_name<span class="token punctuation">:</span> <span class="token string">'พารากอน'</span><span class="token punctuation">,</span>
					avatar<span class="token punctuation">:</span>	<span class="token string">'url'</span> <span class="token comment">// url image profile</span>
				<span class="token punctuation">}</span>
			<span class="token punctuation">]</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>
</code></pre>
<h3 id="leave-request-list-count">Leave request list count</h3>
<h5 id="request-object-example-3">Request object example</h5>
<pre class=" language-javascript"><code class="prism  language-javascript">	<span class="token punctuation">{</span>
		URL<span class="token punctuation">:</span> <span class="token string">'https://cloud.hrtable.com/api/v1/admin/leave/list/count'</span><span class="token punctuation">,</span>
		method<span class="token punctuation">:</span> <span class="token string">'GET'</span><span class="token punctuation">,</span>
	<span class="token punctuation">}</span>

</code></pre>
<h5 id="response-object-sample-3">Response object sample</h5>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">//ย้อนหลัง 30 วัน อ้างอิงจาก created_at</span>
	<span class="token punctuation">{</span>
		success<span class="token punctuation">:</span> <span class="token boolean">true</span><span class="token punctuation">,</span>
		response<span class="token punctuation">:</span> <span class="token punctuation">{</span>
				all<span class="token punctuation">:</span> <span class="token number">10</span> <span class="token comment">//pending + approved + rejected</span>
				pending<span class="token punctuation">:</span> <span class="token number">5</span><span class="token punctuation">,</span>
				approved<span class="token punctuation">:</span> <span class="token number">3</span><span class="token punctuation">,</span>
				rejected<span class="token punctuation">:</span> <span class="token number">2</span><span class="token punctuation">,</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>
</code></pre>
<h3 id="expense-request-list-count">Expense request list count</h3>
<h5 id="request-object-example-4">Request object example</h5>
<pre class=" language-javascript"><code class="prism  language-javascript">	<span class="token punctuation">{</span>
		URL<span class="token punctuation">:</span> <span class="token string">'https://cloud.hrtable.com/api/v1/admin/expense/list/count'</span><span class="token punctuation">,</span>
		method<span class="token punctuation">:</span> <span class="token string">'GET'</span><span class="token punctuation">,</span>
	<span class="token punctuation">}</span>

</code></pre>
<h5 id="response-object-sample-4">Response object sample</h5>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">//ย้อนหลัง 30 วัน อ้างอิงจาก created_at</span>
	<span class="token punctuation">{</span>
		success<span class="token punctuation">:</span> <span class="token boolean">true</span><span class="token punctuation">,</span>
		response<span class="token punctuation">:</span> <span class="token punctuation">{</span>
				all<span class="token punctuation">:</span> <span class="token number">10</span> <span class="token comment">//pending + approved + rejected</span>
				pending<span class="token punctuation">:</span> <span class="token number">5</span><span class="token punctuation">,</span>
				approved<span class="token punctuation">:</span> <span class="token number">3</span><span class="token punctuation">,</span>
				rejected<span class="token punctuation">:</span> <span class="token number">2</span><span class="token punctuation">,</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>
</code></pre>
<h3 id="fieldwork-request-list-count">Fieldwork request list count</h3>
<h5 id="request-object-example-5">Request object example</h5>
<pre class=" language-javascript"><code class="prism  language-javascript">	<span class="token punctuation">{</span>
		URL<span class="token punctuation">:</span> <span class="token string">'https://cloud.hrtable.com/api/v1/admin/fieldword/list/count'</span><span class="token punctuation">,</span>
		method<span class="token punctuation">:</span> <span class="token string">'GET'</span><span class="token punctuation">,</span>
	<span class="token punctuation">}</span>

</code></pre>
<h5 id="response-object-sample-5">Response object sample</h5>
<pre class=" language-javascript"><code class="prism  language-javascript"><span class="token comment">//ย้อนหลัง 30 วัน อ้างอิงจาก created_at</span>
	<span class="token punctuation">{</span>
		success<span class="token punctuation">:</span> <span class="token boolean">true</span><span class="token punctuation">,</span>
		response<span class="token punctuation">:</span> <span class="token punctuation">{</span>
				all<span class="token punctuation">:</span> <span class="token number">10</span> <span class="token comment">//pending + approved + rejected</span>
				pending<span class="token punctuation">:</span> <span class="token number">5</span><span class="token punctuation">,</span>
				approved<span class="token punctuation">:</span> <span class="token number">3</span><span class="token punctuation">,</span>
				rejected<span class="token punctuation">:</span> <span class="token number">2</span><span class="token punctuation">,</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>
</code></pre>

