### threejs-03_Geometry-vertex-position

https://hamhmin.github.io/threejs-03_Geometry-vertex-position/

Geometry-vertex-position 를 이용한 구체 효과

## 배운내용
- OrbitControls 를 이용한 휠과 드래그를 사용하여 카메라제어
- side:DoubleSide 양면의 mesh를 만들어준다.
- flatShading:true material에 flatshading을 넣어줌.
- geometry.attributes.position.array 의 값을 추출하여 mesh의 표면을 울퉁불퉁하게 만들었다. 
(for문, Math.random&sin 사용)

- renderer.setPixelRatio(window.devicePixelRatio > 1 ? 2 : 1); 
기기별 픽셀크기를 다르게 해주어 해상도 저하 방지

