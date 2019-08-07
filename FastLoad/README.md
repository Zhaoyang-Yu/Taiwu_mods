# FastLoad 

加快讀檔進入遊戲，與啟動遊戲的速度

## 使用方法

於 Ctrl+F10 的設定中, 選擇想要的功能

* ### 快速讀取 
	預設開啟。

	使用快取方式跳過重複讀取的主存檔，加快讀取進入遊戲的速度。
    
    開啟後大約能節省 1/3 的讀取時間。
    
	讀取時間如下表，以 0.2.4.0 版測試
     <table>
      <tr>
      	<td></td>
          <td>一般存檔 (40MB)</td>
          <td>大型存檔 (125MB)</td>
      </tr>
      <tr>
      <td>關</td>
      <td>24.151 秒</td>
      <td>54.059 秒</td>
      </tr><tr>
      <td>開</td>
      <td>16.434 秒</td>
      <td>36.055 秒</td>
      </tr>
	</table>

* ### 快速選擇人物
	預設關閉。
	
	進入選擇人物清單時，使用相同的資料，加快啟動遊戲速度
    
    畫面會顯示 **三個一樣的存檔** ，但依然能正常的讀取遊戲
    
    如果你有多個存檔，且檔案都不小(玩了一陣子)，這個功能可以讓你有感的加快啟動遊戲
    
    **!注意!** 建立新角色，請先關閉此功能後，重新啟動遊戲