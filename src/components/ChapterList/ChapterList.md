Array of buttons - selected current chapter

```jsx
import React from "react";
import { ChapterList } from "demo-bsa-reference-rcl";

const selectedChapter = "3";
const title = "Chapter";
const chapters = ["1","2","3","4"];
const onClickChapter = onClick = (chapterKey) => {
  alert("Click" + chapterKey);
};


<ChapterList
  selectedChapter={selectedChapter}
  chapters={chapters}
  title={title}
  onClickChapter={onClickChapter}
  
/>;
```