<table border="1" cellspacing="0" cellpadding="0" width="500">
	<thead>
		<tr>
			<th>api</th>
			<th>接收参数</th>
			<th>返回值</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>/api/remove/:id</td>
			<td>id:number</td>
			<td>string:"删除数据成功"</td>
		</tr>
		<tr>
			<td>/api/find</td>
			<td></td>
			<td>{code:200,msg:"OK",result:[]}</td>
		</tr>
		<tr>
			<td>/api/find/:id</td>
			<td>id:number</td>
			<td>{code:200,msg:"OK",result:{}}</td>
		</tr>
		<tr>
			<td>/api/add</td>
			<td>{
	     name :string,
	     brandCode :string,
	     number :number,
	     price :number,
	     alreadyPay:number,
	     age:number,
	     person:string,
	     email:string,
	     clientDescription:string
     }</td>
			<td>string:"添加数据成功"</td>
		</tr>
		<tr>
			<td>/api/update/:id</td>
			<td>{
			id:number,
	     name?:string,
	     brandCode?:string,
	     number?:number,
	     price?:number,
	     alreadyPay?:number,
	     age?:number,
	     person?:string,
	     email?:string,
	     clientDescription?:string
     }</td>
			<td>string:"更新数据成功"</td>
		</tr>
	</tbody>
</table>
    
