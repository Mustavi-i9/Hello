``` CSS
    @font-face {
        font-family: 'Font';
        src: url('Link');
    }						  /*   font   */

    src: url('Link');         /*   s     */
    background: url('Link');  /*   url   */	
```

<details>
<summary>Gradient</summary>
    
``` css
background: linear-gradient(to right,#FFD4C7,#FF014B); 
		background-clip: text ;
		color: transparent;  /*   bg   */
```    
</details>




<details>
<summary>Universal (fw)</summary>
	
 ``` html
<style>
	* {
		margin: 0;
		padding: 0;
	}
	body {
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center; 
		font-family: sans-serif;
		flex-wrap: wrap;
		column-gap: 1rem;
		margin: 1rem 0;
		background: #383838;
	} 
</style>
```
</details>
