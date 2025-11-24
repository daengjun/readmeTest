<table>
  <tr>
    <td valign="top" width="520">
      <img src="app/src/main/assets/DB.png" width="500" />
    </td>

    <td valign="top" style="padding-left:18px;">

      <!-- 오른쪽 블록 전체를 가운데로 보내는 컨테이너 -->
      <div align="center">

        <!-- 리스트 자체를 가운데에 놓고, 내부는 가운데정렬 -->
        <ol style="
          display: inline-block;
          margin: 0;
          padding-left: 0;
          list-style-position: inside;
          text-align: center;
        ">
          <li><b>id</b> - 메모의 아이디 (PK)</li>
          <li><b>content</b> - 메모 내용</li>
          <li><b>date</b> - 메모 날짜</li>
          <li><b>isDeleted</b> - 삭제 유무 (휴지통 여부)</li>
          <li><b>folderName</b> - 폴더명</li>
        </ol>

      </div>

    </td>
  </tr>
</table>
