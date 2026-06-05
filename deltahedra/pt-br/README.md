<link rel="stylesheet" href="../../scripts/style.css">
<meta charset="utf-8">
<link rel="icon" type="image/png" href="../vr/salas/imagens/icone.png">
<h2>Visualização de Poliedros com Realidade Virtual (RV) em A-frame</h2>
<b>autor:</b> Paulo Henrique Siqueira - Universidade Federal do Paraná
<br><b>contato:</b> <a href="#"> paulohscwb@gmail.com </a>
<br><a href="https://paulohscwb.github.io/polyhedra3/deltahedra/">english version</a>
<form style="margin: 0 auto; float:right; text-align:right; width:100%; margin-bottom:15px;">
	<select id="url" onchange="urlHandler(this.value)" style="color:royalblue;">
		<option disabled selected>Mais sólidos:</option>
		<option value="../../catalangems/pt-br/">Gemas de Catalan</option>
		<option value="../../dragon-archimedes/pt-br/">Fractais do dragão de Arquimedes e Catalan</option>
		<option value="../../kites/pt-br/">Estrelas com pipas</option>
		<option value="../../araucaria/pt-br/">Araucárias com poliedros</option>
		<option value="../../dragon-nonconvex/pt-br/">Fractais de dragão de poliedros não convexos</option>
		<option value="../../fractal-catalan/pt-br/">Fractais de Catalan</option>
		<option disabled value="../../deltahedra/pt-br/">Deltaedros não convexos</option>
		<!--<option value="../../unicorn-platonic/pt-br/">Fractais do unicórnio de Platão</option>
		<option value="../../dragon-catalan/pt-br/">Fractais do dragão de Catalan</option>
		<option value="../../fractalnonconvex1/pt-br/">Fractais de poliedros não convexos</option>
		<option value="../../truncated-archimedes/pt-br/">Poliedros Arquimedianos truncados</option>
		<option value="../../unicorn-catalan/pt-br/">Fractais do unicórnio de Catalan</option>
		<option value="../../fractalnonconvex2/pt-br/">Fractais de poliedros não convexos 2</option>
		<option value="../../unicorn-archimedes/pt-br/">Fractais do unicórnio de Arquimedes</option>
		<option value="../../fractalnonconvex3/pt-br/">Fractais de poliedros não convexos 3</option>
		<option value="../../truncated-catalan/pt-br/">Poliedros de Catalan truncados</option>
		<option value="../../unicorn-nonconvex1/pt-br/">Fractais do unicórnio de poliedros não convexos</option>
		<option value="../../dragon-nonconvex2/pt-br/">Fractais de dragão de poliedros não convexos 2</option>
		<option value="../../unicorn-nonconvex2/pt-br/">Fractais do unicórnio de poliedros não convexos 2</option>
		<option value="../../fractalnonconvex4/pt-br/">Fractais de poliedros não convexos 4</option>
		<option value="../../dragon-nonconvex3/pt-br/">Fractais de dragão de poliedros não convexos 3</option>
		<option value="../../fractalnonconvex5/pt-br/">Fractais de poliedros não convexos 5</option>
		<option value="../../unicorn-nonconvex3/pt-br/">Fractais do unicórnio de poliedros não convexos 3</option>
		<option value="../../fractalnonconvex6/pt-br/">Fractais de poliedros não convexos 6</option>-->
	</select>
</form>
<script>
function urlHandler(value) {                               
    window.location.assign(`${value}`);
}
</script>

<p id="p1"></p>
  <h2 align="center"><img src="../vr/salas/imagens/icone.png" style="margin-bottom:-10px" width="45"> Deltaedros não convexos</h2>
  Henry Martyn Cundy identificou 17 deltaedros côncavos (1952), levando a descoberta publicada por Roger Kaufman (2008) de que existem pelo menos 40 exemplos desse tipo. Os deltaedros são compostos somente por triângulos equiláteros, e existem apenas oito deltaedros convexos: tetraedro, octaedro, icosaedro, dipirâmide triangular (sólido de Johnson J12), dipirâmide pentagonal (J13), disfenoide snub (J84), prisma triaumentado triangular (J51) e dipirâmide quadrada giroalongada (J17).
  <br>Este trabalho mostra alguns deltaedros não convexos modelados para visualização em Realidade Virtual.
 <p align="center"><a href="#m3d">Modelos 3D</a><span>&nbsp;&nbsp;|&nbsp;&nbsp;</span><a href="../../pt-br/">Página Inicial</a></p>
<hr>
  <p align="center"><img src="../vr/salas/videos/video1.gif" style="max-width: 85%; border-radius:5px;" loading="lazy" alt="VR deltahedra"/></p> 
<hr>
<h3 id="m3d" align="center">Modelos 3D</h3>
<!--<iframe width="560" height="315" style="max-width:100%" src="https://www.youtube.com/embed/videoseries?list=PLy0I_lGW8HxU7g9x5hkKKNULwWAdRiCHW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->
<h4>1. Tetraedro aumentado</h4>
<a href="../vr/01_Tetraugmented_Tetrahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/1A.png" class="foto" alt="Tetraedro aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo tetraédrico regular, ao qual são anexadas "tampas" tetraédricas (aumentos) em suas quatro faces.
 <br><b>faces:</b> 12  |  <b>arestas:</b> 18  |  <b>vértices:</b> 8
 <br>
<hr>
<h4>2. Tetraedro giro-aumentado</h4>
<a href="../vr/02_Tetragyraugmented_Tetrahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/2A.png" class="foto" alt="Tetraedro giro-aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo tetraédrico regular, ao qual são anexadas "tampas" octaédricas (aumentos) em suas quatro faces.
 <br><b>faces:</b> 28  |  <b>arestas:</b> 42  |  <b>vértices:</b> 16
 <br>
<hr>
<h4>3. Octaedro aumentado</h4>
<a href="../vr/03_Octagyraugmented_Octahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/3A.png" class="foto" alt="Octaedro aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo tetraédrico regular, ao qual são anexadas "tampas" octaédricas (aumentos) em suas quatro faces.
 <br><b>faces:</b> 56  |  <b>arestas:</b> 84  |  <b>vértices:</b> 30
 <br>
<hr>
<h4>4. Octaedro escavado</h4>
<a href="../vr/04_Octa_excavated_Octahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/4A.png" class="foto" alt="Octaedro escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo octaédrico regular, ao qual são escavados tetraedros regulares em suas oito faces.
 <br><b>faces:</b> 24  |  <b>arestas:</b> 36  |  <b>vértices:</b> 14
 <br>
<hr>
<h4>5. Cubo aumentado</h4>
<a href="../vr/05_Hexaugmented_Cube.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/5A.png" class="foto" alt="Cubo aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo cúbico regular, ao qual são anexadas "tampas" em formato de pirâmides quadradas (aumentos) em suas seis faces.
 <br><b>faces:</b> 24  |  <b>arestas:</b> 36  |  <b>vértices:</b> 14
 <br>
<hr>
<h4>6. Cubo escavado</h4>
<a href="../vr/06_Excavated_Cube.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/6A.png" class="foto" alt="Cubo escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo cúbico regular, ao qual são excavadas pirâmides quadradas em suas seis faces.
 <br><b>faces:</b> 24  |  <b>arestas:</b> 36  |  <b>vértices:</b> 14
 <br>
<hr>
<h4>7. Dodecaedro escavado</h4>
<a href="../vr/07_Dodekexcavated_Dodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/7A.png" class="foto" alt="Dodecaedro escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo dodecaédrico regular, ao qual são escavadas pirâmides pentagonais em suas doze faces.
 <br><b>faces:</b> 60  |  <b>arestas:</b> 90  |  <b>vértices:</b> 32
 <br>
<hr>
<h4>8. Dodecaedro aumentado</h4>
<a href="../vr/08_Dodecaugmented_Dodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/8A.png" class="foto" alt="Dodecaedro aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo dodecaédrico regular, ao qual são anexadas "tampas" em formato de pirâmides pentagonais (aumentos) em suas doze faces.
 <br><b>faces:</b> 60  |  <b>arestas:</b> 90  |  <b>vértices:</b> 32
 <br>
<hr>
<h4>9. Dodecaedro snub aumentado</h4>
<a href="../vr/09_Dodecaugmented_Snub_Icosidodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/9A.png" class="foto" alt="Dodecaedro snub aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo dodecaédrico snub regular, ao qual são anexadas "tampas" em formato de pirâmides pentagonais (aumentos) em suas doze faces pentagonais.
 <br><b>faces:</b> 140  |  <b>arestas:</b> 210  |  <b>vértices:</b> 72
 <br>
<hr>
<h4>10. Dodecaedro snub escavado</h4>
<a href="../vr/10_Dodekexcavated_Snub_Icosidodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/10A.png" class="foto" alt="Dodecaedro snub escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo dodecaédrico snub regular, ao qual são escavadas pirâmides pentagonais em suas doze faces pentagonais.
 <br><b>faces:</b> 140  |  <b>arestas:</b> 210  |  <b>vértices:</b> 72
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">back to top</a></p>
<h4>11. Rombicuboctaedro aumentado</h4>
<a href="../vr/11_RhombicuboctahedronAugmented.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/11A.png" class="foto" alt="Rombicuboctaedro aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo rombicuboctaédrico, ao qual são anexadas "tampas" em formato de pirâmides quadradas (aumentos) em suas faces quadradas.
 <br><b>faces:</b> 80  |  <b>arestas:</b> 120  |  <b>vértices:</b> 42
 <br>
<hr>
<h4>12. Rombicuboctaedro escavado</h4>
<a href="../vr/12_RhombicuboctahedronExcaveted.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/12A.png" class="foto" alt="Rombicuboctaedro escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo rombicuboctaédrico, ao qual são escavadas pirâmides quadradas em suas faces quadradas.
 <br><b>faces:</b> 80  |  <b>arestas:</b> 120  |  <b>vértices:</b> 42
 <br>
<hr>
<h4>13. Icosidodecaedro escavado</h4>
<a href="../vr/13_Dodekexcavated_Icosidodecahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/13A.png" class="foto" alt="Icosidodecaedro escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo icosidodecaédrico, ao qual são escavadas pirâmides pentagonais em suas faces pentagonais.
 <br><b>faces:</b> 80  |  <b>arestas:</b> 120  |  <b>vértices:</b> 42
 <br>
<hr>
<h4>14. Cubo snub aumentado</h4>
<a href="../vr/14_Hexaugmented_Snub_Cube.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/14A.png" class="foto" alt="Cubo snub aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de cubo snub, ao qual são anexadas "tampas" em formato de pirâmides quadradas (aumentos) em suas faces quadradas.
 <br><b>faces:</b> 56  |  <b>arestas:</b> 84  |  <b>vértices:</b> 30
 <br>
<hr>
<h4>15. Cubo snub escavado</h4>
<a href="../vr/15_Hexexcavated_Snub_Cube.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/15A.png" class="foto" alt="Cubo snub escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de cubo snub, ao qual são escavadas pirâmides quadradas em suas faces quadradas.
 <br><b>faces:</b> 56  |  <b>arestas:</b> 84  |  <b>vértices:</b> 30
 <br>
<hr>
<h4>16. Pequeno icosicosidodecaedro snub escavado</h4>
<a href="../vr/16_Dodekexcavated_Seside.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/16A.png" class="foto" alt="Pequeno icosicosidodecaedro snub escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de pequeno icosicosidodecaedro snub, ao qual são escavadas pirâmides pentagrâmicas em suas faces pentagrâmicas.
 <br><b>faces:</b> 160  |  <b>arestas:</b> 240  |  <b>vértices:</b> 82
 <br>
<hr>
<h4>17. Pequeno icosicosidodecaedro snub aumentado</h4>
<a href="../vr/17_Dodecaugmented_Seside.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/17A.png" class="foto" alt="Pequeno icosicosidodecaedro snub aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de pequeno icosicosidodecaedro snub, ao qual são anexadas "tampas" em formato de pirâmides pentagrâmicas (aumentos) em suas faces pentagrâmicas.
 <br><b>faces:</b> 160  |  <b>arestas:</b> 240  |  <b>vértices:</b> 82
 <br>
<hr>
<h4>18. Grande icosaedro aumentado</h4>
<a href="../vr/18_Tetraugmented_Gike.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/18A.png" class="foto" alt="Grande icosaedro tetra-aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de grande icosaedro, ao qual são anexadas "tampas" em formato de tetraedros regulares (aumentos) em quatro faces.
 <br><b>faces:</b> 28  |  <b>arestas:</b> 42  |  <b>vértices:</b> 16
 <br>
<hr>
<h4>19. Grande dodecaedro estrelado escavado</h4>
<a href="../vr/19_Dodekexcavated_Gissid.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/19A.png" class="foto" alt="Grande dodecaedro estrelado escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de grande dodecaedro estrelado, ao qual são escavadas pirâmides pentagrâmicas em suas faces pentagrâmicas.
 <br><b>faces:</b> 60  |  <b>arestas:</b> 90  |  <b>vértices:</b> 32
 <br>
<hr>
<h4>20. Grande icosaedro escavado</h4>
<a href="../vr/20_Icosagyrexcavated_Gike.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/20A.png" class="foto" alt="Grande icosaedro escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de grande icosaedro, ao qual são escavados octaedros regulares em suas faces.
 <br><b>faces:</b> 140  |  <b>arestas:</b> 210  |  <b>vértices:</b> 72
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">voltar ao topo</a></p>
<h4>21. Grande icosidodecaedro ditrigonal escavado</h4>
<a href="../vr/21_Dodekexcavated_Gidtid.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/21A.png" class="foto" alt="Grande icosidodecaedro ditrigonal escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de grande icosidodecaedro ditrigonal, ao qual são escavadas pirâmides pentagrâmicas em suas faces pentagrâmicas.
 <br><b>faces:</b> 80  |  <b>arestas:</b> 120  |  <b>vértices:</b> 42
 <br>
<hr>
<h4>22. Hexaedro truncado estrelado aumentado</h4>
<a href="../vr/22_Octaugmented_Quith.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/22A.png" class="foto" alt="Hexaedro truncado estrelado aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de hexaedro truncado estrelado, ao qual são anexadas "tampas" em formato de pirâmides octogrâmicas (aumentos) em suas faces octogrâmicas.
 <br><b>faces:</b> 56  |  <b>arestas:</b> 84  |  <b>vértices:</b> 30
 <br>
<hr>
<h4>23. Hexaedro truncado estrelado escavado</h4>
<a href="../vr/23_Octaexcavated_Quith.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/23A.png" class="foto" alt="Hexaedro truncado estrelado escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de hexaedro truncado estrelado, ao qual são escavadas pirâmides octogrâmicas em suas faces octogrâmicas.
 <br><b>faces:</b> 56  |  <b>arestas:</b> 84  |  <b>vértices:</b> 30
 <br>
<hr>
<h4>24. Pequeno icosidodecaedro ditrigonal aumentado</h4>
<a href="../vr/24_Dodecaugmented_Sidtid.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/24A.png" class="foto" alt="Pequeno icosidodecaedro ditrigonal aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de pequeno icosidodecaedro ditrigonal, ao qual são anexadas "tampas" em formato de pirâmides pentagrâmicas (aumentos) em suas faces pentagrâmicas.
 <br><b>faces:</b> 80  |  <b>arestas:</b> 120  |  <b>vértices:</b> 42
 <br>
<hr>
<h4>25. Pequeno icosidodecaedro ditrigonal escavado</h4>
<a href="../vr/25_Dodekexcavated_Sidtid.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/25A.png" class="foto" alt="Pequeno icosidodecaedro ditrigonal escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de pequeno icosidodecaedro ditrigonal, ao qual são escavadas pirâmides pentagrâmicas em suas faces pentagrâmicas.
 <br><b>faces:</b> 80  |  <b>arestas:</b> 120  |  <b>vértices:</b> 42
 <br>
<hr>
<h4>26. Octaedro di-escavado</h4>
<a href="../vr/26_Diexcavated_Octahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/26A.png" class="foto" alt="Octaedro di-escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de octaedro, ao qual são escavados tetraedros em duas faces paralelas.
  <br><b>faces:</b> 12  |  <b>arestas:</b> 18  |  <b>vértices:</b> 8
 <br>
<hr>
<h4>27. Antiprisma quadrado di-escavado</h4>
<a href="../vr/27_Diexcavated_Square_Antiprism.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/27A.png" class="foto" alt="Antiprisma quadrado di-escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de antiprisma quadrado, ao qual são escavadas pirâmides quadradas em suas faces quadradas.
  <br><b>faces:</b> 16  |  <b>arestas:</b> 24  |  <b>vértices:</b> 10
 <br>
<hr>
<h4>28. Antiprisma pentagonal di-escavado</h4>
<a href="../vr/28_Diexcavated_Pentagonal_Antiprism.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/28A.png" class="foto" alt="Antiprisma pentagonal di-escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de antiprisma pentagonal, ao qual são escavadas pirâmides pentagonais em suas faces pentagonais.
  <br><b>faces:</b> 20  |  <b>arestas:</b> 30  |  <b>vértices:</b> 12
 <br>
<hr>
<h4>29. Icosaedro tetrambiado</h4>
<a href="../vr/29_Tetrambiated_Icosahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/29A.png" class="foto" alt="Icosaedro tetrambiado"></a>
 <br>Este poliedro é formado por quatro conjuntos de quatro triângulos dispostos tetraedricamente no icosaedro, combinados simetricamente com um conjunto de dez triângulos equiláteros, gerando um deltaedro de Cundy com 44 faces.
  <br><b>faces:</b> 44  |  <b>arestas:</b> 66  |  <b>vértices:</b> 24
 <br>
<hr>
<h4>30. Icosaedro hexasfeniado</h4>
<a href="../vr/30_Hexaspheniated_Icosahedron.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/30A.png" class="foto" alt="Icosaedro hexasfeniado"></a>
 <br>Esse poliedro é formado pela combinação de estruturas esfenóides (cunhas tetraédricas), unidas a uma estrutura básica de icosaedro.
  <br><b>faces:</b> 44  |  <b>arestas:</b> 66  |  <b>vértices:</b> 24
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">voltar ao topo</a></p>

<h4>31. Antiprisma pentagrâmico aumentado</h4>
<a href="../vr/33_PentagrammicAntiprismAugmented.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/31A.png" class="foto" alt="Antiprisma pentagrâmico aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de antiprisma pentagrâmico, ao qual são anexadas "tampas" em formato de pirâmides pentagrâmicas (aumentos) em suas faces pentagrâmicas.
  <br><b>faces:</b> 20  |  <b>arestas:</b> 30  |  <b>vértices:</b> 12
 <br>
<hr>
<h4>32. Antiprisma pentagrâmico escavado</h4>
<a href="../vr/34_PentagrammicAntiprismExcavated.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/32A.png" class="foto" alt="Antiprisma pentagrâmico escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de antiprisma pentagrâmico, ao qual são escavadas pirâmides pentagrâmicas em suas faces pentagrâmicas.
  <br><b>faces:</b> 20  |  <b>arestas:</b> 30  |  <b>vértices:</b> 12
 <br>
<hr>
<h4>33. Antiprisma cruzado pentagrâmico aumentado</h4>
<a href="../vr/31_PentagrammicCrossedAntiprismAugmented.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/33A.png" class="foto" alt="Antiprisma cruzado pentagrâmico aumentado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de antiprisma cruzado pentagrâmico, ao qual são anexadas "tampas" em formato de pirâmides pentagrâmicas (aumentos) em suas faces pentagrâmicas.
  <br><b>faces:</b> 20  |  <b>arestas:</b> 30  |  <b>vértices:</b> 12
 <br>
<hr>
<h4>34. Antiprisma cruzado pentagrâmico escavado</h4>
<a href="../vr/32_PentagrammicCrossedAntiprismExcavated.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="../ar/34A.png" class="foto" alt="Antiprisma cruzado pentagrâmico escavado"></a>
 <br>Este deltaedro é construído a partir de um núcleo de antiprisma cruzado pentagrâmico, ao qual são escavadas pirâmides pentagrâmicas em suas faces pentagrâmicas.
  <br><b>faces:</b> 20  |  <b>arestas:</b> 30  |  <b>vértices:</b> 12
 <br>
<hr>

<h4>31. Deltaedro de Möbius</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius24.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/119A.png" class="foto" alt="Deltaedro de Möbius"></a>
 <br>Os deltaedros de Möbius são simplesmente isômeros das versões do triângulo de Möbius do tetraedro (24 faces), cubo e dodecaedro.
  <br><b>faces:</b> 24  |  <b>arestas:</b> 36  |  <b>vértices:</b> 14
 <br>
<hr>
<h4>32. Hexaedro octakis de Möbius</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius48a.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/118A.png" class="foto" alt="Hexaedro octakis de Möbius"></a>
 <br>O hexaedro octakis é um deltaedro de Möbius com 48 faces derivado do cubo e do triacontaedro rômbico medial.
  <br><b>faces:</b> 48  |  <b>arestas:</b> 72  |  <b>vértices:</b> 26
 <br>
<hr>
<h4>33. Octaedro hexakis de Möbius</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius48b.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/117A.png" class="foto" alt="Octaedro hexakis de Möbius"></a>
 <br>O octaedro hexakis é um deltaedro de Möbius com 48 faces derivado do cubo e do triacontaedro rômbico medial.
  <br><b>faces:</b> 48  |  <b>arestas:</b> 72  |  <b>vértices:</b> 26
 <br>
<hr>
<h4>34. Icosaedro hexakis de Möbius</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius120a.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/116A.png" class="foto" alt="Icosaedro hexakis de Möbius"></a>
 <br>O icosaedro hexakis é um deltaedro de Möbius com 120 faces derivado do icosaedro e do grande triacontaedro rômbico.
  <br><b>faces:</b> 120  |  <b>arestas:</b> 180  |  <b>vértices:</b> 62
 <br>
<hr>
<h4>35. Dodecaedro 10-akis de Möbius</h4>
<a href="https://paulohscwb.github.io/polyhedra/nonconvex/vr/mobius120b.htm" target="_blank" title="modelo 3D" class="fotoA"><img src="https://paulohscwb.github.io/polyhedra/nonconvex/ar/115A.png" class="foto" alt="Dodecaedro 10-akis de Möbius"></a>
 <br>O Dodecaedro 10-akis é um deltaedro de Möbius com 120 faces derivado do dodecaedro e do grande triacontaedro rômbico.
  <br><b>faces:</b> 120  |  <b>arestas:</b> 180  |  <b>vértices:</b> 62
 <br>
<hr>
<p class="topop"><a href="#p1" class="topo">voltar ao topo</a></p>

<br><a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" loading="lazy"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Non-convex deltahedra: visualization with Virtual Reality</span> de <a xmlns:cc="http://creativecommons.org/ns#" href="https://paulohscwb.github.io/polyhedra3/deltahedra/pt-br/" property="cc:attributionName" rel="cc:attributionURL">Paulo Henrique Siqueira</a> está licenciado com uma Licença <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Atribuição-NãoComercial-SemDerivações 4.0 Internacional</a>.

<h4>Como citar este trabalho:</h4> 
<p>Siqueira, P.H., "Non-convex deltahedra: visualization with Virtual Reality". Disponível em: <https://paulohscwb.github.io/polyhedra3/deltahedra/pt-br/>, Junho de 2026.</p>
<!--<a target="_blank" href="https://doi.org/10.5281/zenodo.14502405"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.14502405.svg" alt="DOI"></a>-->
<br><br><b>Referências:</b>
<br>Weisstein, Eric W. "Archimedean Solid" From MathWorld-A Wolfram Web Resource. <a href="http://mathworld.wolfram.com/ArchimedeanSolid.html" target="_blank">http://mathworld.wolfram.com/ArchimedeanSolid.html</a>
<br>McCooey, D. I. "Visual Polyhedra". <a href="http://dmccooey.com/polyhedra/" target="_blank">http://dmccooey.com/polyhedra/</a>
<br>Cundy, H. M. "Deltahedra". Math. Gaz. v. 36, pp. 263-266, 1952
<br>Kaufman, R. "The Cundy Deltahedra". <a href="http://www.interocitors.com/polyhedra/Deltahedra/Cundy" target="_blank">http://www.interocitors.com/polyhedra/Deltahedra/Cundy</a>