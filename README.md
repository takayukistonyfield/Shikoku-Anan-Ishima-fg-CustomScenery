# Shikoku-Anan-Ishima-fg-CustomScenery
Scenery data for FlightGear  
Ishima area in the city of Anan, Tokushima Prefecture, Shikoku region, Japan

Copyright (C) 2025 takayuki

These data are free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

These data are distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with these data.  If not, see <https://www.gnu.org/licenses/>.

FlightGear 用シーナリーデータ  
日本 四国地方 徳島県 阿南市 伊島地域

Copyright (C) 2025 takayuki

これらのデータはフリーソフトウェアです。あなたはこれを、フリーソフトウェ
ア財団によって発行されたGNU 一般公衆利用許諾書（バージョン3か、それ以降
のバージョンのうちどれか）が定める条件の下で再頒布または改変することが
できます。

これらのデータは有用であることを願って頒布されますが、**全くの無保証**で
す。**商業可能性の保証や特定目的への適合性は、言外に示されたものも含め、
全く存在しません。** 詳しくはGNU 一般公衆利用許諾書をご覧ください。

あなたはこれらのデータと共に、GNU 一般公衆利用許諾書のコピーを一部受け取っ
ているはずです。もし受け取っていなければ、
<https://www.gnu.org/licenses/> をご覧ください。

- - -

These are scenery data for the open-source flight simulator [FlightGear](https://www.flightgear.org/) and cover the Ishima area in Tokushima Prefecture, Japan. They were built by takayuki using [terragear-windows](https://github.com/SH-M/terragear-windows/).

- Terrain data are derived from the [1/25000 Vegetation Map "Tokushima Prefecture" GIS data](https://www.biodic.go.jp/trialSystem/EN/info/vg67.html), provided by the Biodiversity Center of Japan, Nature Conservation Bureau, Ministry of the Environment.

- Elevation data are based on [3 arc-second resolution data from Viewfinder Panoramas](http://viewfinderpanoramas.org/Coverage%20map%20viewfinderpanoramas_org3.htm) by Jonathan de Ferranti. Terrafit parameters conform to Scenery 2.0 (`terrafit -m 50 -x 20000 -e 5`).

These scenery data do not include roads, buildings and others. To incorporate additional elements, create symbolic links or junctions in this directory that point to the *Buildings*, *Models*, *Pylons*, and *Roads* directories within *TerraSync* directory.

これらのデータはオープンソースのフライトシミュレータ FlightGear([日本語サイト](http://flightgear.jpn.org/),[公式サイト](https://www.flightgear.org/)) 用の徳島県伊島地域シーナリーデータです。これらのシーナリーデータは [terragear-windows](https://github.com/SH-M/terragear-windows/) を用いて takayuki が作成しました。

- 地形データは、環境省生物多様性センターの [1/25000 植生図 都道府県別「徳島県」GIS データ](http://gis.biodic.go.jp/webgis/sc-025.html?kind=vg67)に基づいています。

- 標高データは、Jonathan de Ferranti による [Viewfinder Panoramas の解像度3秒のデータ](http://viewfinderpanoramas.org/Coverage%20map%20viewfinderpanoramas_org3.htm)を使用しました。地形の解像度をコントロールする terrafit パラメータは Scenery2.0 に準拠し、`terrafit -m 50 -x 20000 -e 5` としました。

これらのシーナリーデータには道路や建物等は含まれていません。このシーナリーのディレクトリの下に、*TerraSync* ディレクトリの下の *Buildings*・*Models*・*Pylons*・*Roads* ディレクトリへのシンボリックリンクまたはジャンクションを作成してください。
