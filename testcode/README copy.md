# ARwork
using three.js<br>
https://github.com/immersive-web <br>
https://web.dev/vr-comes-to-the-web/<br>
https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API<br>
https://github.com/immersive-web/hit-test/blob/master/hit-testing-explainer.md 
https://klausw.github.io/three.js/examples/ <br><p> 필수참조문서<br><br>
https://developers.google.com/ar/discover/supported-devices 사용가능한 스마트폰

https://klausw.github.io/a-frame-car-sample/index.html AR화면에서 터치요소 (자동차 조종)

https://doc.babylonjs.com/how_to/webxr_augmented_reality three.js 대신 babylon.js 사용한 AR

# 0920
art hit test : https://github.com/ptyoiy/ARwork/blob/master/webxr_ar_hittest.html<br>
https://threejs.org/examples/#webxr_ar_hittest<br>
https://github.com/mrdoob/three.js/blob/master/examples/webxr_ar_hittest.html<br>

# 1002
dom-overlay예제 : https://klausw.github.io/three.js/examples/webvr_lorenzattractor.html <br>

# 1009
3D 모델 관리자 추가

# 1016
3D 모델 회전, 이동 추가(dat.gui)

# 1025
거리측정 통합 - 모드변경으로 사용가능한 기능 변경

# 1029
jquery를 사용해, 제어판 조작시엔 onSelect함수가 작동하지 않게함

# 1108
pickHelper 클래스로 물체 선택/제거 기능 추가

# 남은 내용
기기 내부저장소에서 gltf 가져오기(사용자 정의 3d모델 목록) 기능 추가 <br>
원판 대신 터치로 물체 놓기 <br>
3d 모델 크기압축<br>
1. Draco를 사용해 크기 압축 - gltf-pipeline라는 도구를 사용 <br>
2. LOD+mesh-simplify 사용해 크기를 줄인 모델을 따로 준비해 먼저 로딩 <br>
<hr>
로그인기능 통합

# 참고해봄직한 자료
// hit test 다른버전
https://github.com/ptyoiy/ARwork/blob/master/hit-test.html

//물체

//https://threejs.org/examples/#webgl_interactive_voxelpainter //
//https://github.com/mrdoob/three.js/blob/master/examples/webgl_interactive_voxelpainter.html 	/// 마우스 클릭 해서 생성 제거

// 물체 선택 
https://threejs.org/examples/#webgl_math_obb
https://github.com/mrdoob/three.js/blob/master/examples/webgl_math_obb.html

// 물체에 마우스올리면 강조표시
https://threejs.org/examples/#webgl_postprocessing_outline
https://github.com/mrdoob/three.js/blob/master/examples/webgl_postprocessing_outline.html

//물체 클릭시 광원 변경
https://threejs.org/examples/#webgl_postprocessing_unreal_bloom_selective
https://github.com/mrdoob/three.js/blob/master/examples/webgl_postprocessing_unreal_bloom_selective.html

//물체 회전 및 크기 변경 및 이동
https://threejs.org/examples/#misc_animation_authoring
https://github.com/mrdoob/three.js/blob/master/examples/misc_animation_authoring.html
https://threejs.org/examples/#misc_controls_transform
https://github.com/mrdoob/three.js/blob/master/examples/misc_controls_transform.html

//물체 이동
https://threejs.org/examples/#misc_controls_drag
https://github.com/mrdoob/three.js/blob/master/examples/misc_controls_drag.html


//메뉴바들
https://threejs.org/examples/#webgl_geometry_teapot
https://github.com/mrdoob/three.js/blob/master/examples/webgl_geometry_teapot.html	//메뉴바 굿

https://threejs.org/examples/#webgl_lights_rectarealight
https://github.com/mrdoob/three.js/blob/master/examples/webgl_lights_rectarealight.html

https://threejs.org/examples/#webgl_marchingcubes
https://github.com/mrdoob/three.js/blob/master/examples/webgl_marchingcubes.html

https://threejs.org/examples/#webgl_loader_3mf
https://github.com/mrdoob/three.js/blob/master/examples/webgl_loader_3mf.html		// 메뉴바 클릭으로 물체 변경

https://threejs.org/examples/#webgl_loader_obj2_options
https://github.com/mrdoob/three.js/blob/master/examples/webgl_loader_obj2_options.html	//메뉴바 왼쪽

https://threejs.org/examples/#webgl_materials_blending_custom
https://github.com/mrdoob/three.js/blob/master/examples/webgl_materials_blending_custom.html	//메뉴바 굿

//배경 사진 해놓고 물체 
https://threejs.org/examples/#webgl_materials_cubemap_refraction
https://github.com/mrdoob/three.js/blob/master/examples/webgl_materials_cubemap_refraction.html


쓸때없는거
https://threejs.org/examples/#webgl_points_sprites
https://github.com/mrdoob/three.js/blob/master/examples/webgl_points_sprites.html
//메뉴바
https://threejs.org/examples/#webgl_fire
https://github.com/mrdoob/three.js/blob/master/examples/webgl_fire.html

//메인 이미지
https://threejs.org/examples/#webgl_shadowmap
https://github.com/mrdoob/three.js/blob/master/examples/webgl_shadowmap.html
https://threejs.org/examples/#webgl_shadowmap_performance
https://github.com/mrdoob/three.js/blob/master/examples/webgl_shadowmap_performance.html

//단계별 실습 튜토리얼
https://stemkoski.github.io/Three.js/
//모델
https://github.com/stemkoski/stemkoski.github.com/blob/master/Three.js/Model.html

작업자: 이호준, 곽규한 
