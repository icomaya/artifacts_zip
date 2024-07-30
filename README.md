# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


### 적용 방법
설치, 사용방법 

0. 코드를 다운로드합니다.

터미널에서 아래의 명령어를 실행합니다.
1. npm i
2. npm start 를 터미널에서 실행하면 서버가 개설되고 

localhost:3000 주소로 접속가능합니다!

3. 클로드에서 생성한 아티팩트(슬라이드)를 추가하고 싶을때, 
프로젝트 폴더의 /src/components/slides/ 폴더에 파일이름.js 파일을 생성하고 클로드에서 생성한 내용을 붙여넣기 합니다.

(이 때, 기존 slide1.js 파일의 구조를 사용해야하는데 이부분은 AI에게 변환을 요청할 수 있습니다. 

프롬프트 : 

이 코드를 아래의 스타일로 바꿔줘
import React from 'react';

class Slide1_1 {
  static title = "AI를 어디에 써야 하는가?";
  static chapterNumber = "1.1";

  static Content() {
    return (<> ~~~ </>);
  }
}
export default Slide1_1;

![KakaoTalk_20240730_152555324](https://github.com/user-attachments/assets/f2b10a0e-b913-48b3-9d10-2a17369b5c41)

그 후, App.js파일의 16번 라인에 사진과같이 새롭게 추가한 슬라이드파일을 추가해주면 됩니다!
5~13번 라인,
16번 라인만 수정하면 슬라이드가 (비교적) 쉽게 연결되도록 만들었습니다!!

### '구현 결과'

![KakaoTalk_20240730_152128290](https://github.com/user-attachments/assets/760c471b-6de4-435b-b8ba-2bb981b933f2)

위의 형태의 아티팩트를 아래와 같이 목차로 묶어 생성해줍니다.

![KakaoTalk_20240730_152151389](https://github.com/user-attachments/assets/bd729aab-61bc-4154-af5e-392352b0333e)

#### 출처 : https://github.com/woogim
