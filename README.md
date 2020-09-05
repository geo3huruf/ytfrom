# YouTube Scrape
A YouTube search scraping API
## Get search results
The base url to get search results, is as follows:<br>
```
http://youtube-scrape.herokuapp.com/api/search
```
The url query options are as follows:
<table>
  <thead>
    	<tr>
        <th>Query</th>
        <th>Type</th>
        <th>Description</th>
    	</tr>
  </thead>
  <tbody>
		<tr>
        <td>q</td>
        <td>String</td>
        <td>YouTube search query</td>
    	</tr>
    	<tr>
        <td>page</td>
        <td>Number</td>
        <td>The page of YouTube search results</td>
    	</tr>
  </tbody>
</table>

Note that if no page is specified the default is 1
Here is an example call:
```
http://youtube-scrape.herokuapp.com/api/search?q=herman%20fassett&page=1
```
