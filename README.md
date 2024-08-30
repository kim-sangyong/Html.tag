
${\textsf{\color{red}img 태그 사용 시}}$<br>
= ${\textsf{\color{red}img 태그 사용 시}}$ ${\textsf{\color{red}loading='lazy'}}$ 라는 속성을 쓸 수있다. 이 속성은 이미지가 화면에 실제로 나타날 때까지 로딩을 지연시키는 기능을 제공한다.
이 속성을 사용하면 초기 페이지 로드 속도를 개선하고, 사용자가 실제로 보게 될 때까지 이미지 로딩을 미룰 수 있다.
즉 ( 스크롤을 내려서 img가 보이기 전까지 로드 되지 않으므 네트워크 리소스 절약 가능하다!!! )
많은 이미지가 포함된 페이지나 큰 이미지 파일의 경우에 유용하다고 한다. (페이지의 로드 속도를 개선하기 위해 img가 많이 없어도 쓰는거 추천.)
단, 화면에 바로 보이는 img나, 배너 이미지, 히어로 이미지 등등... 에는 사용하는거 비추천, 빨리 사진이 보여져야 하므로 비추천이다.

${\textsf{\color{red}svg 태그}}$<br>
${\textsf{\color{red}SVG (Scalable Vector Graphics)}}$ 는 XML 기반의 벡터 그래픽 형식이다. 웹에서 이미지나 도형을 표시할 때 자주 사용된다.
SVG는 백터 기반이라서 이미지가 확대되거나 축소되어도 해상도가 손실되지 않는다.
SVG 요소는 HTML 문서의 일부로 포함될 수 있고, CSS와 JavaScript로 스타일링하고 조작할 수 있으며 애니메이션 적용도 가능하다.

${\textsf{\color{red}path 요소}}$<br>
${\textsf{\color{red}path}}$ 요소는 SVG에서 가장 강력하고 유연한 도형 요소 중 하나이다. 직선, 곡선, 호 등의 복잡한 도형을 단일 요소로 정의할 수 있습니다.
${\textsf{\color{red}path}}$요소는 복잡한 도형과 곡선을 정의하는 데 사용되며, d 속성의 명령어들을 통해 다양한 경로를 그릴 수 있다.
즉, path 요소로 경로를 줘서 도형을 만들 수 있다.
${\textsf{\color{red}d 속성 :}}$ <path> 요소의 경로를 정의하는 속성이다. 이 속성에 다양한 명령어를 사용해 경로를 그린다.
${\textsf{\color{red}stroke 속성 :}}$ 경로의 외곽선 색상을 정의한다.
${\textsf{\color{red}stroke-width 속성 :}}$ 외곽선의 두께를 설정한다.
${\textsf{\color{red}fill 속성 :}}$ 도형 내부의 채우기 색상을 설정한다.





