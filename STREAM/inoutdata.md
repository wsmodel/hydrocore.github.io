---
sort: 3
---

# 3. 입출력 자료의 설정

자료 구축의 가능성을 고려하여 STREAM 구동을 위해 요구되는 시공간 자료를 정의하고 이를 모델 개발에 반영하였다(Table 1). 시계열 자료로는 강수량, 기온, 이슬점 온도, 운량, 풍속 및 대기압 등을 포함한 기상자료와 모델 보정과 검정을 위한 유량, 수질 등의 관측자료가 요구된다. 공간자료로는 지형, 토지이용, 식생, 토양, 지질, 하천형상에 대한 자료가 필요하며, 이들 자료는 GIS 분석도구를 이용하여 STREAM 입력 자료형식으로 변환되어 사용된다.

STREAM은 모의 결과를 시계열 자료, 공간 자료, 물질수지 자료 등의 다양한 형식으로 제시한다. 시계열 자료는 사용자가 지정한 격자, 링크, 노드에서의 모의결과를 시계열 형식으로 출력한다. 공간 자료는 사용자가 지정하는 시간에 전체 유역의 특정 모의결과를 지도 형태로 출력하며, 물질수지 자료는 전체유역에 대한 물질수지의 시간적 변동을 시계열 형식으로 출력한다.

Table 1. The model input data required for STREAM

|Data|	Attributes|
|---|---|
|Weather|rainfall, air temperature, dew-point temperature, solar radiation, wind speed, atmospheric pressure|
|Topology|elevation, slope, flow direction, flow accumulation|
|Land use|land use classification, impervious surface area ratio, dyke height|
|Vegetation|vegetation density, canopy storage capacity of rainfall interception, surface roughness, crop height, root depth, crop coefficient, leaf area index at each of the growth stages, soil cohesion increase by root reinforcement, incorporation rate of plant residue, application of fertilizer and manure|
|Soil|depth, water contents at saturation, field capacity and wilting point, and residual water content, saturated hydraulic conductivity, fractions of sediment particle size classes, detachability and cohesion of the top soil, volume fraction of the interactive zone around macro pores, equilibrium coefficient for C, N, P adsorption|
|Geology (aquifer)|depth, water contents at saturation, saturated hydraulic conductivity, groundwater recession constant|
|Channel|channel (stream or sewer) width and depth, bed roughness|