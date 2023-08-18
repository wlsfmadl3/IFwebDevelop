# IF - Web 개발
김서율, 이승민, 김진규, 신동흠, 노광민, 안영빈 제작 참여

태성고등학교 입시포털 제작을 목표로 함.

프레임워크 'SvelteKit' 사용

***

Failed to resolve import "fsevents" ... 해결하기!!!
프로젝트 파일 내부의 vite.config.js 파일을 수정합니다.
알아서 잘 적절히...
```
export default defineConfig({
	plugins: [sveltekit()],
	test: {
		include: ['src/**/*.{test,spec}.{js,ts}']
	},
	server: {
		hmr: {
			overlay : false
		}
	}
});
```
이렇게 수정합니다.

문제 자체를 해결하진 못하지만, 페이지를 넘어가면서 뜨는 오류 오버레이를 더 이상 보여주지 않습니다.
