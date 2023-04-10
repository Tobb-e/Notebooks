# Stable Diffusion Cheatsheet
<body>
	<table>
		<tr>
      <th>Expression</th>
			<th>Equivalent Emphasis</th>
			<th>Escape characters</th>
		</tr>
		<tr>
			<td>[[[word]]]</td>
			<td>(word:0.73)</td>
			<td></td>
		</tr>
		<tr>
			<td>[[word]]</td>
			<td>(word:0.81)</td>
			<td></td>
		</tr>
		<tr>
			<td>[word]</td>
			<td>(word:0.9)</td>
			<td>\[word\] or "[word]"</td>
		</tr>
		<tr>
			<td>(word)</td>
			<td>(word:1.1)</td>
			<td>\(word\) or "(word)"</td>
		</tr>
		<tr>
			<td>((word)</td>
			<td>(word:1.21)</td>
			<td></td>
		</tr>
		<tr>
			<td>(((word)))</td>
			<td>(word:1.33)</td>
			<td></td>
		</tr>
	</table>
</body>
</html>
