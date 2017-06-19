# Wiki

## 작성법

### 0. 기본사항

1. 요약은 챕터별로 진행합니다.

2. 작업하신 파일을 [wiki](wiki/) 폴더 안에 `chXX.md` 라는 이름으로 업로드합니다.

3. [index.md](index.md) 파일에 순서에 맞게 `{% include_relative wiki/chXX.md %}` 를 추가합니다.

마크다운의 기본적인 문법은 https://gist.github.com/ihoneymon/652be052a0727ad59601 을 참고하시면 됩니다.

커밋하기전에 꼭 preview changes를 눌러 문법이 옳았는지 확인해주세요.

### 1. 스타일 가이드

- 대단원 명 앞에는 #, 중단원 명 앞에는 ##, 소단원 명 앞에는 ###을 붙여줍니다.

- 코드블럭은 \`\`\`cpp, \`\`\`로 감쌉니다. \`는 숫자 1 왼쪽에 있는 기호입니다.

```cpp
#include <iostream>

using namespace std;

int main()
{
    cout << "hello world" << "\n";
}
```
(raw를 클릭하여 원본을 봐보세요.)

- 코드에서 들여쓰기는 4개의 공백 합니다.

- 작업이 끝나면 중단원별로 진행상황을 기록해주세요.(표 아직 안 만들어짐)

