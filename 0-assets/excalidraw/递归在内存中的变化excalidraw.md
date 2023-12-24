---
due: 2023-12-08 
excalidraw-plugin: parsed
tags: excalidraw C语言

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
递归中return的结果是累加的 ^Mph1Govi

void Reverse(struct Node *p)
{
    if(p->next == NULL)
    {
        head = p;
        return 0;
    }
    Reverse(p->next);
    struct Node*q = p->next;
    q->next =p;
    p->next = NULL;
}
 ^6UcF7kdH

栈帧 ^AwhNKuOs

head头指针 ^HtL5LQR5

Reverse(100) ^RzNXDu50

Reverse(200) ^sRF4IcUv

Reverse(150) ^hWiwT9Sl

Reverse(250) ^Qf2AtnkA

第一次递 ^r9AWw9Vs

第二次递 ^RCcu9C1H

第三次递 ^zy96QdAr

return 0; ^kHobLjHf

第二次归 ^cY4x4eYO

第三次归 ^80lGU4La

p=150 ^k1Pxu2Ui

第一次归 ^GcnnutBE

q->next = 150(p) ^CcmTdlKw

p->next = NULL ^yLqOE0eI

2 ^FMxK3Ehn

200 ^qiwFcD6Z

6 ^x6zexoVi

150 ^KQaoqsBu

5  ^bpS0DMjw

4 ^4xOnbx01

100 ^yCKMXfit

200 ^WY81QNOp

150 ^oXezAeWL

250 ^xPN6zHZQ

p ^gK6YrsCa

q ^GX2vlRZ9

q = 250 ^LcVCl616

150 ^uZ4P43jr

NULL ^kOsVHY9W

p=200 ^IzqlpCmb

q=150
q->next = 200(p)
p->next = NULL ^KD9AWyjD

2 ^Ieg2FdfO

200 ^vk4VxYeP

6 ^hMBYVoBQ

NULL ^IaXbp5lW

5  ^ne3Eu2vS

4 ^L3eOHsGd

100 ^9L7JXVuW

200 ^2rIlteCJ

150 ^S7VC78UM

250 ^9ewW5bpO

p ^sYrjOMNH

q ^Y43GsZEg

150 ^Y2Dd09Sc

200 ^fJritmQk

p=100 ^NUDeRDtX

q=200
q->next = 100(p)
p->next = NULL ^G9WITN9R

2 ^FSiOzdS6

NULL ^C1P6SEru

6 ^9Eiy7PSi

100 ^ysc6hxRB

5  ^V6bFZutb

4 ^DeKkrg2e

100 ^TaVAbgaG

200 ^mR01TQxW

150 ^m55p12xs

250 ^wHQY7TbP

p ^ftrwBe6g

q ^oZ1r5Vlo

150 ^2nxZ2Soi

200 ^NvY7lyv3

递归的两种方式
递的过程中进行
归的过程中进行 ^jBI7V4iH


# Embedded files
08499e533ce526e37b7ed5974b05ff71298968cc: [[Pasted Image 20231208110802_067.png]]

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.10",
	"elements": [
		{
			"type": "embeddable",
			"version": 67,
			"versionNonce": 506506283,
			"isDeleted": false,
			"id": "Kmc3wy0sVQKvtB8FWQIwo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 185.49873707860002,
			"y": -223.00580346441717,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 560,
			"height": 840,
			"seed": 389295103,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703163479023,
			"link": "https://www.bilibili.com/video/BV1Fv4y1f7T1?p=10&vd_source=8b450300cfa6415cb0312754cf65ba30",
			"locked": false,
			"validated": true,
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 173,
			"versionNonce": 463454213,
			"isDeleted": false,
			"id": "Mph1Govi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1007.5506333725675,
			"y": -355.11041596506107,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 260.13995361328125,
			"height": 25,
			"seed": 1893225752,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "递归中return的结果是累加的",
			"rawText": "递归中return的结果是累加的",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "递归中return的结果是累加的",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 243,
			"versionNonce": 1061154507,
			"isDeleted": false,
			"id": "6UcF7kdH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2122.372103386809,
			"y": -38.771473930481875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 289.07977294921875,
			"height": 325,
			"seed": 1466413336,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "void Reverse(struct Node *p)\n{\n    if(p->next == NULL)\n    {\n        head = p;\n        return 0;\n    }\n    Reverse(p->next);\n    struct Node*q = p->next;\n    q->next =p;\n    p->next = NULL;\n}\n",
			"rawText": "void Reverse(struct Node *p)\n{\n    if(p->next == NULL)\n    {\n        head = p;\n        return 0;\n    }\n    Reverse(p->next);\n    struct Node*q = p->next;\n    q->next =p;\n    p->next = NULL;\n}\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "void Reverse(struct Node *p)\n{\n    if(p->next == NULL)\n    {\n        head = p;\n        return 0;\n    }\n    Reverse(p->next);\n    struct Node*q = p->next;\n    q->next =p;\n    p->next = NULL;\n}\n",
			"lineHeight": 1.25,
			"baseline": 318
		},
		{
			"type": "rectangle",
			"version": 212,
			"versionNonce": 1209235301,
			"isDeleted": false,
			"id": "0rc-lB-x-Td7OrPK9uJtQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1128.9647965786728,
			"y": -84.46627008834949,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 188.23529411764707,
			"height": 551.7647058823527,
			"seed": 1349779560,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "srRvglbq4GFfWjoHjMLIE",
					"type": "arrow"
				},
				{
					"id": "xjszlFoRIL3fnoYhVIZtu",
					"type": "arrow"
				},
				{
					"id": "he8_ygwWce7Im84Fk1Hx5",
					"type": "arrow"
				},
				{
					"id": "1OmqZ_RnKGEvcLZlqrCvt",
					"type": "arrow"
				},
				{
					"id": "Hqw_v8GIjBPm7c6rXnRyV",
					"type": "arrow"
				},
				{
					"id": "-bX2pMFhjHbIVT89oNDkG",
					"type": "arrow"
				},
				{
					"id": "9X8ItUl3TERaI1Mi0-F4Z",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 22,
			"versionNonce": 244178283,
			"isDeleted": false,
			"id": "Pgy3ehPIQIzZh7oO4x35B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1788.333778966134,
			"y": 8.33458667557909,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 599,
			"height": 67,
			"seed": 1767949416,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "08499e533ce526e37b7ed5974b05ff71298968cc",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "line",
			"version": 32,
			"versionNonce": 1339638469,
			"isDeleted": false,
			"id": "YhasM0RFNezlIDQNtQlVc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1126.4194831518032,
			"y": 385.05398917900294,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 183.47598215926087,
			"height": 2.457267618204355,
			"seed": 1942445336,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					183.47598215926087,
					2.457267618204355
				]
			]
		},
		{
			"type": "arrow",
			"version": 13,
			"versionNonce": 660928523,
			"isDeleted": false,
			"id": "srRvglbq4GFfWjoHjMLIE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1132.15310759428,
			"y": 385.05398917900294,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 108.11977520099299,
			"height": 27.029943800248247,
			"seed": 155743336,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0rc-lB-x-Td7OrPK9uJtQ",
				"focus": -0.5654801740134897,
				"gap": 3.1883110156073826
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-108.11977520099299,
					27.029943800248247
				]
			]
		},
		{
			"type": "text",
			"version": 22,
			"versionNonce": 663659045,
			"isDeleted": false,
			"id": "AwhNKuOs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1288.599145953293,
			"y": 410.445754567115,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 25,
			"seed": 1848927512,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "栈帧",
			"rawText": "栈帧",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "栈帧",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "line",
			"version": 55,
			"versionNonce": 1472183979,
			"isDeleted": false,
			"id": "UBzv-omruxbafBp3yWiMO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1127.2385723578714,
			"y": 318.7077634874845,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 185.11416057139718,
			"height": 6.552713648545023,
			"seed": 1939133544,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					185.11416057139718,
					6.552713648545023
				]
			]
		},
		{
			"type": "arrow",
			"version": 16,
			"versionNonce": 1411454341,
			"isDeleted": false,
			"id": "Hb5mQNX_YYm2xsj4vyHHW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1844.7607168735524,
			"y": -32.68150591574286,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.8190892060681563,
			"height": 53.24079839442838,
			"seed": 558304536,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0.8190892060681563,
					-53.24079839442838
				]
			]
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 1246277963,
			"isDeleted": false,
			"id": "HtL5LQR5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1863.5997686131193,
			"y": -112.95224811041949,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 105.53996276855469,
			"height": 25,
			"seed": 349095784,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "head头指针",
			"rawText": "head头指针",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "head头指针",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 22,
			"versionNonce": 1624120549,
			"isDeleted": false,
			"id": "RzNXDu50",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1090.3795580848055,
			"y": 346.55679649380085,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 124.29989624023438,
			"height": 25,
			"seed": 265552744,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Reverse(100)",
			"rawText": "Reverse(100)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Reverse(100)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "line",
			"version": 46,
			"versionNonce": 1884966891,
			"isDeleted": false,
			"id": "CRfDakdHAkhRS3kXQj6Xa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1128.8767507700077,
			"y": 253.18062700203416,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 186.7523389835335,
			"height": 4.095446030340668,
			"seed": 1550008168,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					186.7523389835335,
					4.095446030340668
				]
			]
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 354629701,
			"isDeleted": false,
			"id": "sRF4IcUv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1091.1986472908736,
			"y": 280.21057080228246,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 133.11988830566406,
			"height": 25,
			"seed": 736266776,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Reverse(200)",
			"rawText": "Reverse(200)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Reverse(200)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "line",
			"version": 56,
			"versionNonce": 738138763,
			"isDeleted": false,
			"id": "ULj7252HQKIsMPr7GDBgW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1129.6958399760758,
			"y": 184.37713369231136,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 189.20960660173796,
			"height": 6.552713648545023,
			"seed": 642888728,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					189.20960660173796,
					6.552713648545023
				]
			]
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 1795024805,
			"isDeleted": false,
			"id": "hWiwT9Sl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1093.655914909078,
			"y": 208.9498098743552,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 122.89988708496094,
			"height": 25,
			"seed": 1618405480,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Reverse(150)",
			"rawText": "Reverse(150)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Reverse(150)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "line",
			"version": 42,
			"versionNonce": 972132651,
			"isDeleted": false,
			"id": "ysKlOMQrlFe4ZMEtFUG4l",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1125.600393945735,
			"y": 109.02092673404343,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 185.11416057139718,
			"height": 5.733624442476923,
			"seed": 1206424168,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					185.11416057139718,
					5.733624442476923
				]
			]
		},
		{
			"type": "text",
			"version": 34,
			"versionNonce": 1150003973,
			"isDeleted": false,
			"id": "Qf2AtnkA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1095.2940933212144,
			"y": 140.1463165646324,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.71987915039062,
			"height": 25,
			"seed": 537855256,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Reverse(250)",
			"rawText": "Reverse(250)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Reverse(250)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 47,
			"versionNonce": 1536963531,
			"isDeleted": false,
			"id": "xjszlFoRIL3fnoYhVIZtu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1132.15310759428,
			"y": 349.83315331807336,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.32626315801963,
			"height": 66.34622569151838,
			"seed": 1696693352,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0rc-lB-x-Td7OrPK9uJtQ",
				"focus": -0.6640364506463492,
				"gap": 3.1883110156073826
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-48.32626315801963,
					-34.40174665486137
				],
				[
					0,
					-66.34622569151838
				]
			]
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 1649017445,
			"isDeleted": false,
			"id": "r9AWw9Vs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1283.684610716884,
			"y": 301.50689016005373,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 25,
			"seed": 432309864,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "第一次递",
			"rawText": "第一次递",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "第一次递",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 91,
			"versionNonce": 1092190827,
			"isDeleted": false,
			"id": "he8_ygwWce7Im84Fk1Hx5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1132.1416882522499,
			"y": 278.7410284385462,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.32626315801963,
			"height": 66.34622569151838,
			"seed": 1059865960,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0rc-lB-x-Td7OrPK9uJtQ",
				"focus": -0.4566753542421291,
				"gap": 3.176891673577188
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-48.32626315801963,
					-34.40174665486137
				],
				[
					0,
					-66.34622569151838
				]
			]
		},
		{
			"type": "arrow",
			"version": 88,
			"versionNonce": 419851717,
			"isDeleted": false,
			"id": "1OmqZ_RnKGEvcLZlqrCvt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1135.4180450765227,
			"y": 205.8420890984827,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.32626315801963,
			"height": 66.34622569151838,
			"seed": 1548277096,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0rc-lB-x-Td7OrPK9uJtQ",
				"focus": -0.25087058733929707,
				"gap": 6.453248497850041
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-48.32626315801963,
					-34.40174665486137
				],
				[
					0,
					-66.34622569151838
				]
			]
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 859045131,
			"isDeleted": false,
			"id": "RCcu9C1H",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1289.2828640620226,
			"y": 229.2133781170803,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 25,
			"seed": 1935233304,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "第二次递",
			"rawText": "第二次递",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "第二次递",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 1205759269,
			"isDeleted": false,
			"id": "zy96QdAr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1288.4637748559546,
			"y": 153.0380819527444,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 25,
			"seed": 2038170904,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "第三次递",
			"rawText": "第三次递",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "第三次递",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "line",
			"version": 56,
			"versionNonce": 2103845803,
			"isDeleted": false,
			"id": "oaZCqeZdQjL19AQuJZoke",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1126.4194831518032,
			"y": 56.59921754568322,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 183.47598215926087,
			"height": 4.095446030340639,
			"seed": 1313091944,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					183.47598215926087,
					4.095446030340639
				]
			]
		},
		{
			"type": "text",
			"version": 39,
			"versionNonce": 239042693,
			"isDeleted": false,
			"id": "kHobLjHf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1079.73139840592,
			"y": 74.61918007918206,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 89.05992126464844,
			"height": 25,
			"seed": 1631566360,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "return 0;",
			"rawText": "return 0;",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "return 0;",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 109,
			"versionNonce": 400193099,
			"isDeleted": false,
			"id": "Hqw_v8GIjBPm7c6rXnRyV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -933.3462455580196,
			"y": 157.02631705536334,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.678103479133824,
			"height": 62.25077966117777,
			"seed": 1575815192,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0rc-lB-x-Td7OrPK9uJtQ",
				"focus": -0.31218739843674315,
				"gap": 7.383256903005986
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					37.678103479133824,
					27.029943800248247
				],
				[
					0,
					62.25077966117777
				]
			]
		},
		{
			"type": "arrow",
			"version": 120,
			"versionNonce": 1105668069,
			"isDeleted": false,
			"id": "-bX2pMFhjHbIVT89oNDkG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -933.3462455580194,
			"y": 218.45800751047312,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.678103479133824,
			"height": 62.25077966117777,
			"seed": 1026244200,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0rc-lB-x-Td7OrPK9uJtQ",
				"focus": -0.1332956804956702,
				"gap": 7.383256903006213
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					37.678103479133824,
					27.029943800248247
				],
				[
					0,
					62.25077966117777
				]
			]
		},
		{
			"type": "arrow",
			"version": 114,
			"versionNonce": 292254955,
			"isDeleted": false,
			"id": "9X8ItUl3TERaI1Mi0-F4Z",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -934.984423970156,
			"y": 286.44241161412776,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.678103479133824,
			"height": 62.25077966117777,
			"seed": 2075150360,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0rc-lB-x-Td7OrPK9uJtQ",
				"focus": 0.06810009703567167,
				"gap": 5.745078490869673
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					37.678103479133824,
					27.029943800248247
				],
				[
					0,
					62.25077966117777
				]
			]
		},
		{
			"type": "text",
			"version": 114,
			"versionNonce": 618849093,
			"isDeleted": false,
			"id": "cY4x4eYO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -879.2220094426841,
			"y": 226.29516555656448,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 25,
			"seed": 2115912808,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "第二次归",
			"rawText": "第二次归",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "第二次归",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 109,
			"versionNonce": 967024523,
			"isDeleted": false,
			"id": "80lGU4La",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -881.9890280120528,
			"y": 296.53724997468436,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 25,
			"seed": 1657065576,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "ogsMXPshtLd64_ks5-pEm",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "第三次归",
			"rawText": "第三次归",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "第三次归",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 130,
			"versionNonce": 1536176805,
			"isDeleted": false,
			"id": "9LjIyZ2cwYbpANJXITTUF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -785.6235164230054,
			"y": 176.69145286334634,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.97221228345666,
			"height": 1.8423423775629004,
			"seed": 487654168,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "k1Pxu2Ui"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "GcnnutBE",
				"focus": -0.24027123992488125,
				"gap": 15.923310404786434
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					130.97221228345666,
					1.8423423775629004
				]
			]
		},
		{
			"type": "text",
			"version": 12,
			"versionNonce": 180188715,
			"isDeleted": false,
			"id": "k1Pxu2Ui",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -747.0073901396755,
			"y": 165.11262405212779,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 53.739959716796875,
			"height": 25,
			"seed": 1220174440,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "p=150",
			"rawText": "p=150",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "9LjIyZ2cwYbpANJXITTUF",
			"originalText": "p=150",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 143,
			"versionNonce": 580687365,
			"isDeleted": false,
			"id": "hN9nSTFnzKuG6FBbSk7MV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -650.9619460470581,
			"y": 168.38806048655675,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 57.023097345611404,
			"height": 48.52502699310075,
			"seed": 1423520024,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "CcmTdlKw",
				"focus": 1.2664312288061532,
				"gap": 14.757432369967091
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					57.023097345611404,
					-48.52502699310075
				]
			]
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 1403222219,
			"isDeleted": false,
			"id": "GcnnutBE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -881.5468268277918,
			"y": 166.54338144031084,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 25,
			"seed": 963822104,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "9LjIyZ2cwYbpANJXITTUF",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "第一次归",
			"rawText": "第一次归",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "第一次归",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 1157991781,
			"isDeleted": false,
			"id": "CcmTdlKw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -572.5630865816088,
			"y": 123.19342385353292,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 160.4598846435547,
			"height": 25,
			"seed": 280518168,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "hN9nSTFnzKuG6FBbSk7MV",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "q->next = 150(p)",
			"rawText": "q->next = 150(p)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "q->next = 150(p)",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 569386859,
			"isDeleted": false,
			"id": "yLqOE0eI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -580.8641422897151,
			"y": 143.48489336223747,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 154.05990600585938,
			"height": 25,
			"seed": 1045897064,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "p->next = NULL",
			"rawText": "p->next = NULL",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "p->next = NULL",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 176,
			"versionNonce": 1377343685,
			"isDeleted": false,
			"id": "Te3yAFWl9flt6w6bffpHP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -866.7893944578246,
			"y": -53.89576458607053,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 1471288856,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "pEGNn-93oMmGHjI8nPO10",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 107,
			"versionNonce": 1810760203,
			"isDeleted": false,
			"id": "7Rqz4Us_ThIVfbXkVxax5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -724.2879381353314,
			"y": -51.12874601670174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 866255128,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "pEGNn-93oMmGHjI8nPO10",
					"type": "arrow"
				},
				{
					"id": "9Iyrs7ue0AhjnWMNSxtPy",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 95,
			"versionNonce": 326318117,
			"isDeleted": false,
			"id": "8W_IpRjRA-nsbuEllfRpa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -569.3348982506782,
			"y": -52.05108553982467,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 239187304,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "9Iyrs7ue0AhjnWMNSxtPy",
					"type": "arrow"
				},
				{
					"id": "dlwQ2G_GdRCs1NHNECTXt",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 99,
			"versionNonce": 2056751275,
			"isDeleted": false,
			"id": "jBNUJxox-se2KB3Yx5gIx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -428.21695121286893,
			"y": -51.12874601670171,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 909814808,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "dlwQ2G_GdRCs1NHNECTXt",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 331,
			"versionNonce": 1124264837,
			"isDeleted": false,
			"id": "pEGNn-93oMmGHjI8nPO10",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -761.6426888218099,
			"y": -35.49751083313487,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.28188330930254,
			"height": 1.0171081440399234,
			"seed": 761695848,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "qiwFcD6Z",
				"focus": -0.4687983088223349,
				"gap": 10.813373569960618
			},
			"endBinding": {
				"elementId": "7Rqz4Us_ThIVfbXkVxax5",
				"focus": 0.12377850162865994,
				"gap": 5.072867377175896
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					32.28188330930254,
					1.0171081440399234
				]
			]
		},
		{
			"type": "arrow",
			"version": 151,
			"versionNonce": 328678219,
			"isDeleted": false,
			"id": "9Iyrs7ue0AhjnWMNSxtPy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -620.8464869349717,
			"y": -31.990672530767938,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 44.27229710990093,
			"height": 2.767018569368844,
			"seed": 1482537064,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "KQaoqsBu",
				"focus": -0.39925766636963567,
				"gap": 14.255252977832356
			},
			"endBinding": {
				"elementId": "8W_IpRjRA-nsbuEllfRpa",
				"focus": -0.213824034678835,
				"gap": 7.239291574392553
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					44.27229710990093,
					2.767018569368844
				]
			]
		},
		{
			"type": "arrow",
			"version": 346,
			"versionNonce": 17117925,
			"isDeleted": false,
			"id": "dlwQ2G_GdRCs1NHNECTXt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -434.53390326413853,
			"y": -30.145993484522023,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 25.82550664744224,
			"height": 0.9223395231229006,
			"seed": 2136827416,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "jBNUJxox-se2KB3Yx5gIx",
				"focus": -0.07778742835337377,
				"gap": 6.316952051269595
			},
			"endBinding": {
				"elementId": "kOsVHY9W",
				"focus": -0.21961475503669825,
				"gap": 10.355023039868229
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-25.82550664744224,
					-0.9223395231229006
				]
			]
		},
		{
			"type": "line",
			"version": 65,
			"versionNonce": 1665636843,
			"isDeleted": false,
			"id": "u1QkJSijeNIdD-UuNnhrq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -820.6724183016779,
			"y": -53.895764586070555,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 1259914264,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "line",
			"version": 67,
			"versionNonce": 168267333,
			"isDeleted": false,
			"id": "2injQKX-ZYNlRZIjgK982",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -676.8878104681994,
			"y": -51.78993851695569,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 991002216,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "line",
			"version": 67,
			"versionNonce": 649274507,
			"isDeleted": false,
			"id": "dNonAz8_0NbFrxj3WO8Hi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -522.8571101066693,
			"y": -53.6346175632016,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 2113491736,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "line",
			"version": 67,
			"versionNonce": 753368485,
			"isDeleted": false,
			"id": "CM-7dJy-YGyUqHhbE8yuJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -379.8944840226145,
			"y": -53.6346175632016,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 483083112,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "text",
			"version": 44,
			"versionNonce": 362044203,
			"isDeleted": false,
			"id": "FMxK3Ehn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -851.1096225647348,
			"y": -39.13833221610358,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 155028248,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 90,
			"versionNonce": 13795589,
			"isDeleted": false,
			"id": "qiwFcD6Z",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -814.2160416398174,
			"y": -42.82769030859535,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.759979248046875,
			"height": 25,
			"seed": 1996467048,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "pEGNn-93oMmGHjI8nPO10",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "200",
			"rawText": "200",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "200",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 74,
			"versionNonce": 206945739,
			"isDeleted": false,
			"id": "x6zexoVi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -707.2246569575569,
			"y": -35.44897412361186,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 972549144,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 88,
			"versionNonce": 1531320421,
			"isDeleted": false,
			"id": "KQaoqsBu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -666.6417179401478,
			"y": -40.983011262349436,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.53997802734375,
			"height": 25,
			"seed": 67722520,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "9Iyrs7ue0AhjnWMNSxtPy",
					"type": "arrow"
				}
			],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "150",
			"rawText": "150",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "150",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 69,
			"versionNonce": 1980877931,
			"isDeleted": false,
			"id": "bpS0DMjw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -555.9609751653954,
			"y": -39.13833221610358,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.3599853515625,
			"height": 25,
			"seed": 1699959576,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "5 ",
			"rawText": "5 ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5 ",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 87,
			"versionNonce": 101696453,
			"isDeleted": false,
			"id": "4xOnbx01",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -412.0760095582177,
			"y": -43.75002983171828,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1585991784,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 50,
			"versionNonce": 1989347083,
			"isDeleted": false,
			"id": "yCKMXfit",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -828.9734740097844,
			"y": -80.6436107566357,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.93998718261719,
			"height": 25,
			"seed": 1625571608,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "100",
			"rawText": "100",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 894239525,
			"isDeleted": false,
			"id": "WY81QNOp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -686.0108479257294,
			"y": -76.95425266414395,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.759979248046875,
			"height": 25,
			"seed": 104959336,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "200",
			"rawText": "200",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "200",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 1414786475,
			"isDeleted": false,
			"id": "oXezAeWL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -536.5918451798138,
			"y": -76.95425266414392,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.53997802734375,
			"height": 25,
			"seed": 1994514712,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479024,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "150",
			"rawText": "150",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "150",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 1030444677,
			"isDeleted": false,
			"id": "xPN6zHZQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -398.24091671137353,
			"y": -74.18723409477514,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40.35997009277344,
			"height": 25,
			"seed": 238825240,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "250",
			"rawText": "250",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "250",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 33,
			"versionNonce": 578748491,
			"isDeleted": false,
			"id": "m_a51hvY15JJff1EmCfd3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -513.5316313133658,
			"y": 38.260527249345444,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.9206137347478034,
			"height": 41.42761806365496,
			"seed": 582326808,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "gK6YrsCa",
				"focus": 0.05871423367411932,
				"gap": 1
			},
			"endBinding": {
				"elementId": "kOsVHY9W",
				"focus": 0.6097091061745347,
				"gap": 13.738259971163274
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0.9206137347478034,
					-41.42761806365496
				]
			]
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 153632229,
			"isDeleted": false,
			"id": "gK6YrsCa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -519.0673942404785,
			"y": 39.260527249345444,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.8599853515625,
			"height": 25,
			"seed": 832651624,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "m_a51hvY15JJff1EmCfd3",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "p",
			"rawText": "p",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "p",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 65,
			"versionNonce": 720289515,
			"isDeleted": false,
			"id": "xgUuEDd-r18Go4JS4cc0H",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -366.6874802042258,
			"y": 25.425434402501423,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.720747915005404,
			"height": 36.397166541320374,
			"seed": 867329048,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "GX2vlRZ9",
				"focus": 0.27381764849217205,
				"gap": 7.378716184983489
			},
			"endBinding": {
				"elementId": "uZ4P43jr",
				"focus": 0.8465292622841394,
				"gap": 5.933618646653898
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-2.720747915005404,
					-36.397166541320374
				]
			]
		},
		{
			"type": "text",
			"version": 21,
			"versionNonce": 1334917445,
			"isDeleted": false,
			"id": "GX2vlRZ9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -374.26008911017766,
			"y": 32.80415058748491,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.141387939453125,
			"height": 32.37871618498349,
			"seed": 540151144,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "xgUuEDd-r18Go4JS4cc0H",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 25.90297294798679,
			"fontFamily": 1,
			"text": "q",
			"rawText": "q",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "q",
			"lineHeight": 1.25,
			"baseline": 22
		},
		{
			"type": "text",
			"version": 35,
			"versionNonce": 405645707,
			"isDeleted": false,
			"id": "LcVCl616",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -570.7184075353628,
			"y": 99.21259625233625,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 83.61996459960938,
			"height": 25,
			"seed": 1442582552,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "q = 250",
			"rawText": "q = 250",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "q = 250",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 168020133,
			"isDeleted": false,
			"id": "uZ4P43jr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -372.41541006393186,
			"y": -41.90535078547285,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.53997802734375,
			"height": 25,
			"seed": 2094285848,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "xgUuEDd-r18Go4JS4cc0H",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "150",
			"rawText": "150",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "150",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 1601585195,
			"isDeleted": false,
			"id": "kOsVHY9W",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -521.8344128098474,
			"y": -41.90535078547279,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.11997985839844,
			"height": 25,
			"seed": 1759261464,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "dlwQ2G_GdRCs1NHNECTXt",
					"type": "arrow"
				},
				{
					"id": "m_a51hvY15JJff1EmCfd3",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "NULL",
			"rawText": "NULL",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "NULL",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 48,
			"versionNonce": 707619845,
			"isDeleted": false,
			"id": "-nOaLHFRnjx_z6Q8sLurc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -782.8564978536375,
			"y": 237.5635247207765,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 127.28285419096494,
			"height": 3.689358092491716,
			"seed": 2050733080,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "IzqlpCmb"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					127.28285419096494,
					3.689358092491716
				]
			]
		},
		{
			"type": "text",
			"version": 8,
			"versionNonce": 1790116555,
			"isDeleted": false,
			"id": "IzqlpCmb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -746.1221838497288,
			"y": 225.98586424389944,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 63.9599609375,
			"height": 25,
			"seed": 1432855912,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "p=200",
			"rawText": "p=200",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "-nOaLHFRnjx_z6Q8sLurc",
			"originalText": "p=200",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 66,
			"versionNonce": 269198181,
			"isDeleted": false,
			"id": "KD9AWyjD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -592.0737319199875,
			"y": 204.35930188835084,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 170.6798858642578,
			"height": 75,
			"seed": 40362776,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "q=150\nq->next = 200(p)\np->next = NULL",
			"rawText": "q=150\nq->next = 200(p)\np->next = NULL",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "q=150\nq->next = 200(p)\np->next = NULL",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 307,
			"versionNonce": 41841003,
			"isDeleted": false,
			"id": "t7UxKX38MjkMSYLMu3lqi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -403.0831992077716,
			"y": 230.13639209795267,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 927864344,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "eAgviouwVeb9a54Kxgs1A",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 239,
			"versionNonce": 1072426693,
			"isDeleted": false,
			"id": "7ry2ow_2O_ceweWFl670_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -260.58174288527846,
			"y": 232.90341066732148,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 374575896,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "eAgviouwVeb9a54Kxgs1A",
					"type": "arrow"
				},
				{
					"id": "sQp0UK_zsZZSMi_BHMy88",
					"type": "arrow"
				},
				{
					"id": "KSP5iDM1f7MZu7tMavMrf",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 229,
			"versionNonce": 2015562763,
			"isDeleted": false,
			"id": "5y54cp0QdXbaY_3vpAPCF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -105.62870300062525,
			"y": 231.98107114419858,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 1369534488,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "nLPVog1b_YzuPVvIQGQTN",
					"type": "arrow"
				},
				{
					"id": "z7D8e89bwjzfReN_0OjaM",
					"type": "arrow"
				},
				{
					"id": "sQp0UK_zsZZSMi_BHMy88",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 230,
			"versionNonce": 1483460133,
			"isDeleted": false,
			"id": "y3k_e-aakcNWCo3Vug1sN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 35.489244037183994,
			"y": 232.90341066732148,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 19639576,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "nLPVog1b_YzuPVvIQGQTN",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 730,
			"versionNonce": 261837483,
			"isDeleted": false,
			"id": "eAgviouwVeb9a54Kxgs1A",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -297.93649357175684,
			"y": 248.53464585088838,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.28188330930254,
			"height": 1.0171081440399234,
			"seed": 510020120,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "vk4VxYeP",
				"focus": -0.46879830882233087,
				"gap": 10.813373569960731
			},
			"endBinding": {
				"elementId": "7ry2ow_2O_ceweWFl670_",
				"focus": 0.12377850162865994,
				"gap": 5.0728673771758395
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					32.28188330930254,
					1.0171081440399234
				]
			]
		},
		{
			"type": "arrow",
			"version": 662,
			"versionNonce": 1215873413,
			"isDeleted": false,
			"id": "sQp0UK_zsZZSMi_BHMy88",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -111.73478320642187,
			"y": 252.4222312981107,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 47.2501875247425,
			"height": 2.3338190469340248,
			"seed": 1413826328,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "5y54cp0QdXbaY_3vpAPCF",
				"focus": 0.15010966784527943,
				"gap": 6.106080205796616
			},
			"endBinding": {
				"elementId": "IaXbp5lW",
				"focus": 0.05140835111717182,
				"gap": 4.820985901130257
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-47.2501875247425,
					2.3338190469340248
				]
			]
		},
		{
			"type": "arrow",
			"version": 751,
			"versionNonce": 697419083,
			"isDeleted": false,
			"id": "nLPVog1b_YzuPVvIQGQTN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 29.172291985914512,
			"y": 254.11401344270845,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.1855072577938,
			"height": 1.2702819977717468,
			"seed": 1329374232,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "y3k_e-aakcNWCo3Vug1sN",
				"focus": -0.08856946131812878,
				"gap": 6.316952051269482
			},
			"endBinding": {
				"elementId": "fJritmQk",
				"focus": -0.21961475503669967,
				"gap": 10.355023039868342
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-35.1855072577938,
					-1.2702819977717468
				]
			]
		},
		{
			"type": "line",
			"version": 196,
			"versionNonce": 1162889445,
			"isDeleted": false,
			"id": "4e7hI4f3-kWLfjSUyM9lf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -356.96622305162475,
			"y": 230.13639209795267,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 222322968,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "line",
			"version": 198,
			"versionNonce": 761324523,
			"isDeleted": false,
			"id": "OXtPmGuxeEPh3PXDZytB-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -213.18161521814648,
			"y": 232.24221816706753,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 767852056,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "line",
			"version": 198,
			"versionNonce": 8381509,
			"isDeleted": false,
			"id": "77525YWxKt4EW8pZazGAR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -59.15091485661617,
			"y": 230.39753912082162,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 1102904088,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "line",
			"version": 198,
			"versionNonce": 856895115,
			"isDeleted": false,
			"id": "mAVbKcM67O_3-dg03sK9a",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 83.81171122743842,
			"y": 230.39753912082162,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 463329304,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "text",
			"version": 175,
			"versionNonce": 501552037,
			"isDeleted": false,
			"id": "Ieg2FdfO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -387.40342731468184,
			"y": 244.89382446791964,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 526062872,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 221,
			"versionNonce": 1835214123,
			"isDeleted": false,
			"id": "vk4VxYeP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -350.50984638976445,
			"y": 241.2044663754278,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.759979248046875,
			"height": 25,
			"seed": 308851224,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "eAgviouwVeb9a54Kxgs1A",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "200",
			"rawText": "200",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "200",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 205,
			"versionNonce": 1772967685,
			"isDeleted": false,
			"id": "hMBYVoBQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -243.5184617075039,
			"y": 248.58318256041136,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1807396632,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 235,
			"versionNonce": 1404782539,
			"isDeleted": false,
			"id": "IaXbp5lW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -214.92593649069306,
			"y": 243.04914542167373,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.11997985839844,
			"height": 25,
			"seed": 600116248,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "sQp0UK_zsZZSMi_BHMy88",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "NULL",
			"rawText": "NULL",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "NULL",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 200,
			"versionNonce": 1314270821,
			"isDeleted": false,
			"id": "ne3Eu2vS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -92.25477991534228,
			"y": 244.89382446791964,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.3599853515625,
			"height": 25,
			"seed": 75221272,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "5 ",
			"rawText": "5 ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5 ",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 218,
			"versionNonce": 204871275,
			"isDeleted": false,
			"id": "L3eOHsGd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 51.63018569183521,
			"y": 240.2821268523049,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 2035475992,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 181,
			"versionNonce": 179116485,
			"isDeleted": false,
			"id": "9L7JXVuW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -365.2672787597313,
			"y": 203.38854592738753,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.93998718261719,
			"height": 25,
			"seed": 1597924120,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "100",
			"rawText": "100",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 190,
			"versionNonce": 362680587,
			"isDeleted": false,
			"id": "2rIlteCJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -222.30465267567627,
			"y": 207.07790401987924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.759979248046875,
			"height": 25,
			"seed": 1420967960,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "200",
			"rawText": "200",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "200",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 177,
			"versionNonce": 667916581,
			"isDeleted": false,
			"id": "S7VC78UM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -72.88564992976092,
			"y": 207.07790401987924,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.53997802734375,
			"height": 25,
			"seed": 161643800,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "150",
			"rawText": "150",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "150",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 192,
			"versionNonce": 829274027,
			"isDeleted": false,
			"id": "9ewW5bpO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 65.46527853867963,
			"y": 209.84492258924806,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40.35997009277344,
			"height": 25,
			"seed": 260250136,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "250",
			"rawText": "250",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "250",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 465,
			"versionNonce": 791358597,
			"isDeleted": false,
			"id": "KSP5iDM1f7MZu7tMavMrf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -179.8753088236466,
			"y": 326.90438154898345,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.9206137347478034,
			"height": 41.42761806365496,
			"seed": 692590360,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "sYrjOMNH",
				"focus": -1.1653011071164334,
				"gap": 1
			},
			"endBinding": {
				"elementId": "7ry2ow_2O_ceweWFl670_",
				"focus": -0.6317915572611568,
				"gap": 10.145734754351949
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0.9206137347478034,
					-41.42761806365496
				]
			]
		},
		{
			"type": "text",
			"version": 180,
			"versionNonce": 231705163,
			"isDeleted": false,
			"id": "sYrjOMNH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -178.95469508889857,
			"y": 324.21502345649174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.8599853515625,
			"height": 25,
			"seed": 459633688,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "KSP5iDM1f7MZu7tMavMrf",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "p",
			"rawText": "p",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "p",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 430,
			"versionNonce": 545084389,
			"isDeleted": false,
			"id": "z7D8e89bwjzfReN_0OjaM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -45.94391103822761,
			"y": 319.603325840877,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.720747915005404,
			"height": 36.397166541320374,
			"seed": 2077176088,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "5y54cp0QdXbaY_3vpAPCF",
				"focus": -0.08587978336770827,
				"gap": 8.797470091703005
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-2.720747915005404,
					-36.397166541320374
				]
			]
		},
		{
			"type": "text",
			"version": 191,
			"versionNonce": 798886123,
			"isDeleted": false,
			"id": "Y43GsZEg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -51.67184089793352,
			"y": 316.8363072715082,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.141387939453125,
			"height": 32.37871618498349,
			"seed": 33115672,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 25.90297294798679,
			"fontFamily": 1,
			"text": "q",
			"rawText": "q",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "q",
			"lineHeight": 1.25,
			"baseline": 22
		},
		{
			"type": "text",
			"version": 176,
			"versionNonce": 668176197,
			"isDeleted": false,
			"id": "Y2Dd09Sc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 91.2907851861213,
			"y": 242.12680589855037,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.53997802734375,
			"height": 25,
			"seed": 1456982808,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "z7D8e89bwjzfReN_0OjaM",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "150",
			"rawText": "150",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "150",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 185,
			"versionNonce": 476296075,
			"isDeleted": false,
			"id": "fJritmQk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -58.12821755979451,
			"y": 242.12680589855037,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.759979248046875,
			"height": 25,
			"seed": 1692313624,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "nLPVog1b_YzuPVvIQGQTN",
					"type": "arrow"
				},
				{
					"id": "KSP5iDM1f7MZu7tMavMrf",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "200",
			"rawText": "200",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "200",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 21,
			"versionNonce": 327900837,
			"isDeleted": false,
			"id": "ogsMXPshtLd64_ks5-pEm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -787.2907418740756,
			"y": 306.0460616722793,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 154.2827722846264,
			"height": 56.53109213482503,
			"seed": 39494248,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "NUDeRDtX"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "80lGU4La",
				"focus": -0.8481696141217072,
				"gap": 14.69828613797722
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					154.2827722846264,
					56.53109213482503
				]
			]
		},
		{
			"type": "text",
			"version": 8,
			"versionNonce": 1146817067,
			"isDeleted": false,
			"id": "NUDeRDtX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -737.7193401677976,
			"y": 321.8116077396918,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 55.13996887207031,
			"height": 25,
			"seed": 1387053592,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "p=100",
			"rawText": "p=100",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ogsMXPshtLd64_ks5-pEm",
			"originalText": "p=100",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 173163013,
			"isDeleted": false,
			"id": "G9WITN9R",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -574.1214152823397,
			"y": 354.333036204109,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 161.85989379882812,
			"height": 75,
			"seed": 2027258904,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "q=200\nq->next = 100(p)\np->next = NULL",
			"rawText": "q=200\nq->next = 100(p)\np->next = NULL",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "q=200\nq->next = 100(p)\np->next = NULL",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 370,
			"versionNonce": 745442507,
			"isDeleted": false,
			"id": "tWEyyZNFjKzYfc82SSX1A",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -389.07094166413344,
			"y": 417.69663462134577,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 1721780840,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "Y9H9GDWFSQo6SK5YkRy3w",
					"type": "arrow"
				},
				{
					"id": "T0uFpr9DDSqnjWxr7Icek",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 303,
			"versionNonce": 19249509,
			"isDeleted": false,
			"id": "82s5pXYpu9omgP-gMBVW5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -246.5694853416403,
			"y": 420.4636531907146,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 1811594600,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "Tf_KQBPcfqdc6N5i4AWvp",
					"type": "arrow"
				},
				{
					"id": "T0uFpr9DDSqnjWxr7Icek",
					"type": "arrow"
				},
				{
					"id": "YJf6yK8AGYg-u3lYgDh-n",
					"type": "arrow"
				},
				{
					"id": "Y9H9GDWFSQo6SK5YkRy3w",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 290,
			"versionNonce": 1480113003,
			"isDeleted": false,
			"id": "-8IOZ_QuJRUBP-MNM4JSR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -91.6164454569871,
			"y": 419.5413136675917,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 1670303848,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "GZlB4o_W3ETs29yjikw8u",
					"type": "arrow"
				},
				{
					"id": "YJf6yK8AGYg-u3lYgDh-n",
					"type": "arrow"
				},
				{
					"id": "Tf_KQBPcfqdc6N5i4AWvp",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 291,
			"versionNonce": 1901282501,
			"isDeleted": false,
			"id": "jmYW8-qyzDuZEYjoTyi9Y",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 49.50150158082215,
			"y": 420.4636531907146,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.53500802039991,
			"height": 42.42761806365502,
			"seed": 354976616,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "GZlB4o_W3ETs29yjikw8u",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 984,
			"versionNonce": 1946424843,
			"isDeleted": false,
			"id": "Y9H9GDWFSQo6SK5YkRy3w",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -255.7205380394921,
			"y": 438.6752930644946,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 24.187360746736545,
			"height": 1.9189151293740565,
			"seed": 1863571048,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "82s5pXYpu9omgP-gMBVW5",
				"focus": 0.3061751861675147,
				"gap": 9.15105269785181
			},
			"endBinding": {
				"elementId": "C1P6SEru",
				"focus": 0.12329828709385632,
				"gap": 5.469710201499197
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-24.187360746736545,
					1.9189151293740565
				]
			]
		},
		{
			"type": "arrow",
			"version": 879,
			"versionNonce": 1316512805,
			"isDeleted": false,
			"id": "Tf_KQBPcfqdc6N5i4AWvp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -97.72252566278372,
			"y": 440.5177352413092,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 52.475138252959695,
			"height": 3.1750071739098757,
			"seed": 907856232,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "-8IOZ_QuJRUBP-MNM4JSR",
				"focus": 0.15010966784528065,
				"gap": 6.106080205796616
			},
			"endBinding": {
				"elementId": "ysc6hxRB",
				"focus": 0.05140835111716975,
				"gap": 4.820985901130257
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-52.475138252959695,
					3.1750071739098757
				]
			]
		},
		{
			"type": "arrow",
			"version": 938,
			"versionNonce": 1053498539,
			"isDeleted": false,
			"id": "GZlB4o_W3ETs29yjikw8u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 43.18454952955267,
			"y": 441.67425596610155,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.1855072577938,
			"height": 1.2702819977717468,
			"seed": 898587752,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "jmYW8-qyzDuZEYjoTyi9Y",
				"focus": -0.08856946131813001,
				"gap": 6.316952051269482
			},
			"endBinding": {
				"elementId": "NvY7lyv3",
				"focus": -0.21961475503669756,
				"gap": 10.355023039868342
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-35.1855072577938,
					-1.2702819977717468
				]
			]
		},
		{
			"type": "line",
			"version": 257,
			"versionNonce": 1015191429,
			"isDeleted": false,
			"id": "F0fgo7f-egRmsHI8tZ0MB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -342.9539655079866,
			"y": 417.69663462134577,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 1865912168,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "line",
			"version": 259,
			"versionNonce": 876105547,
			"isDeleted": false,
			"id": "6bItARoFjyMKzB2cR6Q-8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -199.16935767450832,
			"y": 419.80246069046063,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 1264673384,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "line",
			"version": 259,
			"versionNonce": 95379173,
			"isDeleted": false,
			"id": "QWYYKRKcVQriQ5wiVq0dh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -45.13865731297801,
			"y": 417.9577816442147,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 1222169960,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "line",
			"version": 259,
			"versionNonce": 1990602219,
			"isDeleted": false,
			"id": "jgv7Zq1XA1NIjXtYkgXUg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 97.82396877107658,
			"y": 417.9577816442147,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.58293901740916,
			"seed": 753526888,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					40.58293901740916
				]
			]
		},
		{
			"type": "text",
			"version": 236,
			"versionNonce": 1351367237,
			"isDeleted": false,
			"id": "FSiOzdS6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -373.3911697710437,
			"y": 432.45406699131274,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 861969256,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 286,
			"versionNonce": 2032089227,
			"isDeleted": false,
			"id": "C1P6SEru",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -336.4975888461263,
			"y": 428.7647088988209,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.11997985839844,
			"height": 25,
			"seed": 1049161320,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "Y9H9GDWFSQo6SK5YkRy3w",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "NULL",
			"rawText": "NULL",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "NULL",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 266,
			"versionNonce": 368486821,
			"isDeleted": false,
			"id": "9Eiy7PSi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -229.50620416386573,
			"y": 436.14342508380446,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 120512872,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 309,
			"versionNonce": 1767763755,
			"isDeleted": false,
			"id": "ysc6hxRB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -187.95863699949086,
			"y": 431.78711903120904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.93998718261719,
			"height": 25,
			"seed": 1285452904,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "Tf_KQBPcfqdc6N5i4AWvp",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "100",
			"rawText": "100",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 261,
			"versionNonce": 1461464325,
			"isDeleted": false,
			"id": "V6bFZutb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -78.24252237170413,
			"y": 432.45406699131274,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.3599853515625,
			"height": 25,
			"seed": 77834088,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "5 ",
			"rawText": "5 ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5 ",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 279,
			"versionNonce": 1506595275,
			"isDeleted": false,
			"id": "DeKkrg2e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 65.64244323547337,
			"y": 427.842369375698,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 193624680,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 242,
			"versionNonce": 326780005,
			"isDeleted": false,
			"id": "TaVAbgaG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -351.25502121609316,
			"y": 390.9487884507806,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 32.93998718261719,
			"height": 25,
			"seed": 1411313000,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "100",
			"rawText": "100",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "100",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 251,
			"versionNonce": 730226795,
			"isDeleted": false,
			"id": "mR01TQxW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -208.2923951320381,
			"y": 394.63814654327234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.759979248046875,
			"height": 25,
			"seed": 397213800,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "200",
			"rawText": "200",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "200",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 238,
			"versionNonce": 2128506821,
			"isDeleted": false,
			"id": "m55p12xs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -58.87339238612276,
			"y": 394.63814654327234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.53997802734375,
			"height": 25,
			"seed": 100709224,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "150",
			"rawText": "150",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "150",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 253,
			"versionNonce": 945101579,
			"isDeleted": false,
			"id": "wHQY7TbP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 79.47753608231778,
			"y": 397.40516511264116,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40.35997009277344,
			"height": 25,
			"seed": 1969620584,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "250",
			"rawText": "250",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "250",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 807,
			"versionNonce": 2003185445,
			"isDeleted": false,
			"id": "T0uFpr9DDSqnjWxr7Icek",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -327.10652959412243,
			"y": 513.2421953993561,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.3802539143831041,
			"height": 42.56065156291885,
			"seed": 313063784,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ftrwBe6g",
				"focus": -0.9400501097649875,
				"gap": 6.77718818352389
			},
			"endBinding": {
				"elementId": "tWEyyZNFjKzYfc82SSX1A",
				"focus": -0.2449810477720662,
				"gap": 10.55729115143646
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0.3802539143831041,
					-42.56065156291885
				]
			]
		},
		{
			"type": "text",
			"version": 291,
			"versionNonce": 1018397099,
			"isDeleted": false,
			"id": "ftrwBe6g",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -327.4693274328822,
			"y": 520.01938358288,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.8599853515625,
			"height": 25,
			"seed": 286624872,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "T0uFpr9DDSqnjWxr7Icek",
					"type": "arrow"
				}
			],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "p",
			"rawText": "p",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "p",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 602,
			"versionNonce": 998179461,
			"isDeleted": false,
			"id": "YJf6yK8AGYg-u3lYgDh-n",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -185.03669469307374,
			"y": 509.5190305365544,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.720747915005404,
			"height": 36.39716654132036,
			"seed": 1517797224,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163479025,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "-8IOZ_QuJRUBP-MNM4JSR",
				"focus": 2.870175115099465,
				"gap": 96.14099715109205
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-2.720747915005404,
					-36.39716654132036
				]
			]
		},
		{
			"type": "text",
			"version": 301,
			"versionNonce": 30151755,
			"isDeleted": false,
			"id": "oZ1r5Vlo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -190.76462455277965,
			"y": 505.57428088104336,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.141387939453125,
			"height": 32.37871618498349,
			"seed": 1058771560,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479026,
			"link": null,
			"locked": false,
			"fontSize": 25.90297294798679,
			"fontFamily": 1,
			"text": "q",
			"rawText": "q",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "q",
			"lineHeight": 1.25,
			"baseline": 22
		},
		{
			"type": "text",
			"version": 237,
			"versionNonce": 1608935909,
			"isDeleted": false,
			"id": "2nxZ2Soi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 105.30304272975945,
			"y": 429.6870484219435,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.53997802734375,
			"height": 25,
			"seed": 634193256,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "YJf6yK8AGYg-u3lYgDh-n",
					"type": "arrow"
				}
			],
			"updated": 1703163479026,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "150",
			"rawText": "150",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "150",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 246,
			"versionNonce": 1199133419,
			"isDeleted": false,
			"id": "NvY7lyv3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -44.11596001615635,
			"y": 429.6870484219435,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.759979248046875,
			"height": 25,
			"seed": 1004017768,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "GZlB4o_W3ETs29yjikw8u",
					"type": "arrow"
				},
				{
					"id": "T0uFpr9DDSqnjWxr7Icek",
					"type": "arrow"
				}
			],
			"updated": 1703163479026,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "200",
			"rawText": "200",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "200",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "text",
			"version": 137,
			"versionNonce": 95020357,
			"isDeleted": false,
			"id": "jBI7V4iH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -885.2718682361292,
			"y": -699.5372975577172,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 140,
			"height": 75,
			"seed": 934021400,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163479026,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "递归的两种方式\n递的过程中进行\n归的过程中进行",
			"rawText": "递归的两种方式\n递的过程中进行\n归的过程中进行",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "递归的两种方式\n递的过程中进行\n归的过程中进行",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"id": "tjivT6nvPV3UokUno1kQR",
			"type": "arrow",
			"x": -319.33296469902825,
			"y": -879.8656115115516,
			"width": 1768.571428571428,
			"height": 771.4285714285713,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 599158789,
			"version": 156,
			"versionNonce": 1747427403,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1703163578675,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					300,
					-440
				],
				[
					728.5714285714284,
					80
				],
				[
					562.8571428571427,
					-634.2857142857142
				],
				[
					1208.5714285714284,
					-220
				],
				[
					991.4285714285711,
					-691.4285714285713
				],
				[
					1768.571428571428,
					-134.28571428571433
				]
			],
			"lastCommittedPoint": [
				1768.571428571428,
				-134.28571428571433
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"text": "🌐app://obsidian.md#addLibrary=https%3A%2F%2Flibraries.excalidraw.com%2Flibraries%2Fg-script%2Fcharts.excalidrawlib&token=Fzjn1HMGNxvc-8zCgtm-N",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 18,
			"id": "B2VcSLMy",
			"type": "text",
			"x": -731.7700164874379,
			"y": -1004.5528005110671,
			"width": 1516.619384765625,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"roundness": null,
			"seed": 76320,
			"version": 9,
			"versionNonce": 1884540773,
			"updated": 1703163482282,
			"isDeleted": true,
			"groupIds": [],
			"boundElements": [],
			"link": null,
			"locked": false,
			"containerId": null,
			"originalText": "🌐app://obsidian.md#addLibrary=https%3A%2F%2Flibraries.excalidraw.com%2Flibraries%2Fg-script%2Fcharts.excalidrawlib&token=Fzjn1HMGNxvc-8zCgtm-N",
			"rawText": "app://obsidian.md#addLibrary=https%3A%2F%2Flibraries.excalidraw.com%2Flibraries%2Fg-script%2Fcharts.excalidrawlib&token=Fzjn1HMGNxvc-8zCgtm-N",
			"lineHeight": 1.25
		},
		{
			"id": "xe1fbSi7xetju0_iHy7aH",
			"type": "embeddable",
			"x": -2071.293826011247,
			"y": -1805.3861338444003,
			"width": 3255,
			"height": 1595,
			"angle": 0,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"seed": 2121642507,
			"version": 82,
			"versionNonce": 132727563,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1703163532403,
			"link": "https://libraries.excalidraw.com/?target=_blank&referrer=app%3A%2F%2Fobsidian.md&useHash=true&token=Fzjn1HMGNxvc-8zCgtm-N&theme=light&version=2&sort=downloadsTotal",
			"locked": false,
			"validated": true,
			"scale": [
				1,
				1
			]
		},
		{
			"type": "ellipse",
			"version": 165,
			"versionNonce": 1332660549,
			"isDeleted": true,
			"id": "oWdyuvmTk1WMBoDRLVhUZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 711.1055273644638,
			"y": -1181.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1715244363,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 179,
			"versionNonce": 984684939,
			"isDeleted": true,
			"id": "JTs-SdURFeEYv-ivJsy4l",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 508.1055273644638,
			"y": -1039.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 426945515,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 201,
			"versionNonce": 1471109285,
			"isDeleted": true,
			"id": "sJGEDvpLy3urZ5qBhVG2I",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 908.1055273644638,
			"y": -1007.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1236006539,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 209,
			"versionNonce": 1074507819,
			"isDeleted": true,
			"id": "u56e4ILtLD_U-AkAyLB7T",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 376.1055273644638,
			"y": -863.9638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1168305451,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 253,
			"versionNonce": 1541864453,
			"isDeleted": true,
			"id": "tNAgyKSxQxo6rIB0aVUeZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 608.1055273644638,
			"y": -856.9638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 549588939,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 215,
			"versionNonce": 1998222027,
			"isDeleted": true,
			"id": "sQr_9WX4upjp7qGSEEm-P",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1032.1055273644638,
			"y": -852.9638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 488889963,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 227,
			"versionNonce": 1947415397,
			"isDeleted": true,
			"id": "s-2uCq-G1LPw4O3bb9wm8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 807.1055273644638,
			"y": -856.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1435687179,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 61,
			"versionNonce": 1886904683,
			"isDeleted": true,
			"id": "zQQFg-RnT80O2K1S9jaAt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 716.1055273644638,
			"y": -1141.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 160,
			"height": 112,
			"seed": 663322539,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-160,
					112
				]
			]
		},
		{
			"type": "line",
			"version": 50,
			"versionNonce": 1551990469,
			"isDeleted": true,
			"id": "rXe5xwwQx4j2GaOqNBbAm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 514.1055273644638,
			"y": -994.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 104,
			"height": 133,
			"seed": 1563578955,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-104,
					133
				]
			]
		},
		{
			"type": "line",
			"version": 53,
			"versionNonce": 1164868619,
			"isDeleted": true,
			"id": "H4bq0eyBnRXr1xTEh0lRO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 550.1055273644638,
			"y": -989.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 74,
			"height": 135,
			"seed": 392679659,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					74,
					135
				]
			]
		},
		{
			"type": "line",
			"version": 60,
			"versionNonce": 1808752165,
			"isDeleted": true,
			"id": "Hi0WO8J0bjSq3ido9IuPi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 761.1055273644638,
			"y": -1138.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 159,
			"height": 135,
			"seed": 2008316811,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					159,
					135
				]
			]
		},
		{
			"type": "line",
			"version": 53,
			"versionNonce": 33079979,
			"isDeleted": true,
			"id": "yTS7eNC9U1m4GeIST3sNU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 917.1055273644638,
			"y": -957.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 69,
			"height": 104,
			"seed": 173199915,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-69,
					104
				]
			]
		},
		{
			"type": "line",
			"version": 59,
			"versionNonce": 1223315845,
			"isDeleted": true,
			"id": "AKs5UddEHT8__I6Itiwm5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 955.1055273644638,
			"y": -958.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 102,
			"height": 106,
			"seed": 1882019019,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					102,
					106
				]
			]
		},
		{
			"type": "ellipse",
			"version": 225,
			"versionNonce": 1321284939,
			"isDeleted": true,
			"id": "P2LApcS9TO9inrymujBum",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 173.1055273644638,
			"y": -721.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1222542187,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 247,
			"versionNonce": 1628428517,
			"isDeleted": true,
			"id": "bDAcMZbce5DfvDO24NS1j",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 573.1055273644638,
			"y": -689.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1555095051,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 255,
			"versionNonce": 1528976363,
			"isDeleted": true,
			"id": "giusbW_jSDTT12lxbdVEv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 41.105527364463796,
			"y": -546.2138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 111076523,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 299,
			"versionNonce": 500003909,
			"isDeleted": true,
			"id": "JGsp4m9pZG5Xi70kjCWvs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 273.1055273644638,
			"y": -539.2138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1582503755,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 261,
			"versionNonce": 119971467,
			"isDeleted": true,
			"id": "PZ7M_nBlno7Mq6pxcjX_j",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 697.1055273644638,
			"y": -535.2138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 573044203,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 273,
			"versionNonce": 1526768549,
			"isDeleted": true,
			"id": "fiNc1q1eCbWvp9EAhS_mV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 472.1055273644638,
			"y": -538.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1630011531,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 107,
			"versionNonce": 1300796715,
			"isDeleted": true,
			"id": "7iNCL_rvR1jG5SkM0J2gG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 381.1055273644638,
			"y": -823.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 160,
			"height": 112,
			"seed": 1695397675,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-160,
					112
				]
			]
		},
		{
			"type": "line",
			"version": 96,
			"versionNonce": 483845893,
			"isDeleted": true,
			"id": "sg0IitwLE-BGcw6_GRNYR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 179.1055273644638,
			"y": -676.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 104,
			"height": 133,
			"seed": 1547934155,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-104,
					133
				]
			]
		},
		{
			"type": "line",
			"version": 99,
			"versionNonce": 1840429003,
			"isDeleted": true,
			"id": "8A03WDGhGmst8L84WsNzO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 215.1055273644638,
			"y": -671.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 74,
			"height": 135,
			"seed": 1139026027,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					74,
					135
				]
			]
		},
		{
			"type": "line",
			"version": 106,
			"versionNonce": 97369701,
			"isDeleted": true,
			"id": "f-VFTxhYlY0axmKWO0Kzp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 426.1055273644638,
			"y": -820.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 159,
			"height": 135,
			"seed": 297394955,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					159,
					135
				]
			]
		},
		{
			"type": "line",
			"version": 99,
			"versionNonce": 1438615147,
			"isDeleted": true,
			"id": "xe_JPOwP2rVXNxraqbpSv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 582.1055273644638,
			"y": -639.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 69,
			"height": 104,
			"seed": 507464107,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-69,
					104
				]
			]
		},
		{
			"type": "line",
			"version": 105,
			"versionNonce": 213035461,
			"isDeleted": true,
			"id": "zshoEkassA9_ly2LO0hq1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 620.1055273644638,
			"y": -640.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 102,
			"height": 106,
			"seed": 1319033931,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					102,
					106
				]
			]
		},
		{
			"type": "ellipse",
			"version": 294,
			"versionNonce": 1283031307,
			"isDeleted": true,
			"id": "tnH8YHk0wO1mPqVb09XoJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 736.1055273644638,
			"y": -702.2138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 2125667051,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 93,
			"versionNonce": 1923295525,
			"isDeleted": true,
			"id": "ChI584B8IHG03fqw8Kl9H",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 654.1055273644638,
			"y": -808.7138257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 93.61270985417059,
			"height": 111.91737067289648,
			"seed": 721847691,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					93.61270985417059,
					111.91737067289648
				]
			]
		},
		{
			"type": "line",
			"version": 99,
			"versionNonce": 1532700587,
			"isDeleted": true,
			"id": "zMe1MOWjTw-dl70KciLXm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 400.1055273644638,
			"y": -807.9638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 25.821907542888084,
			"height": 137.84037868790324,
			"seed": 1523817515,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					25.821907542888084,
					137.84037868790324
				]
			]
		},
		{
			"type": "ellipse",
			"version": 323,
			"versionNonce": 2030877829,
			"isDeleted": true,
			"id": "YPmyNZaaq3Nxj95qTsRCd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 400.1055273644638,
			"y": -669.4638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1241833163,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 295,
			"versionNonce": 2022636107,
			"isDeleted": true,
			"id": "1rsIbMb3dtfGEbG6DZ0VH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 274.1055273644638,
			"y": -952.9638257972658,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1395969387,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 164,
			"versionNonce": 1470948325,
			"isDeleted": true,
			"id": "x4h1M23pCbGaT3VNpUmiY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 506.06871712694067,
			"y": -1012.9221022139997,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 184.9366262704134,
			"height": 68.2046018107049,
			"seed": 430827531,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-184.9366262704134,
					68.2046018107049
				]
			]
		},
		{
			"type": "line",
			"version": 216,
			"versionNonce": 1894742251,
			"isDeleted": true,
			"id": "iIrYZ_kHjL79VmNzcEsxO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 729.9816121193903,
			"y": -1128.6432874086386,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 3.318258057441426,
			"height": 180.43202336136252,
			"seed": 1936371371,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678046,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-3.318258057441426,
					180.43202336136252
				]
			]
		},
		{
			"type": "ellipse",
			"version": 256,
			"versionNonce": 1922113349,
			"isDeleted": true,
			"id": "fNmk1hvaKm0n7GJZysZXz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 700.9388606977968,
			"y": -946.2971591305991,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 320184651,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 247,
			"versionNonce": 302457739,
			"isDeleted": true,
			"id": "-1MZGGzoij7ustiCAdrZD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1160.8714003803375,
			"y": -701.0193813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1913208811,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 259,
			"versionNonce": 1343680165,
			"isDeleted": true,
			"id": "5aC3zrShhby4OGW9E_SKQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 935.8714003803375,
			"y": -704.5193813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 2052065931,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 85,
			"versionNonce": 336624171,
			"isDeleted": true,
			"id": "_MMoFnlVEUA1-YbXXV5bq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1045.8714003803375,
			"y": -805.5193813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 69,
			"height": 104,
			"seed": 1889829163,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-69,
					104
				]
			]
		},
		{
			"type": "line",
			"version": 91,
			"versionNonce": 1324077573,
			"isDeleted": true,
			"id": "2Do38WwI0DlsbXxFMZv3v",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1083.8714003803375,
			"y": -806.5193813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 102,
			"height": 106,
			"seed": 510731211,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					102,
					106
				]
			]
		},
		{
			"type": "ellipse",
			"version": 284,
			"versionNonce": 1140194507,
			"isDeleted": true,
			"id": "xaGl0mG8v1bBce-B9A8Kh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1283.3714003803377,
			"y": -549.7693813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1003516523,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 296,
			"versionNonce": 470632805,
			"isDeleted": true,
			"id": "tr6lr1b3hOvqCfT_56Cuc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1058.3714003803377,
			"y": -553.2693813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 428666123,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 122,
			"versionNonce": 1834101611,
			"isDeleted": true,
			"id": "rizCjAVeC4tPWbnXvcoFp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1168.3714003803377,
			"y": -654.2693813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 69,
			"height": 104,
			"seed": 186717099,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-69,
					104
				]
			]
		},
		{
			"type": "line",
			"version": 128,
			"versionNonce": 1757992133,
			"isDeleted": true,
			"id": "DLY4xA5RcW5VxG5ROZ_LU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1206.3714003803377,
			"y": -655.2693813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 102,
			"height": 106,
			"seed": 280454731,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					102,
					106
				]
			]
		},
		{
			"type": "ellipse",
			"version": 322,
			"versionNonce": 74417675,
			"isDeleted": true,
			"id": "43MwkwXb9t209Ey2vWt9T",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 837.871400380337,
			"y": -550.7693813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 54,
			"height": 54,
			"seed": 1093297387,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 148,
			"versionNonce": 1622930469,
			"isDeleted": true,
			"id": "Tyy6uLU1PZnEYdre_IgoM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 947.871400380337,
			"y": -651.7693813528213,
			"strokeColor": "#000000",
			"backgroundColor": "#40c057",
			"width": 69,
			"height": 104,
			"seed": 1946455947,
			"groupIds": [
				"7AAAGLK42YqtFh57A-JFH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703163678047,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-69,
					104
				]
			]
		},
		{
			"id": "2xhHT5Pzt7st6I_T6Ei7A",
			"type": "arrow",
			"x": 1543.5241781581146,
			"y": 417.2772456313055,
			"width": 634.2857142857144,
			"height": 905.7142857142858,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1750003429,
			"version": 48,
			"versionNonce": 639328331,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1703163734716,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					634.2857142857144,
					-905.7142857142858
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "9bVSff1t-u6Tlntu36_Nv",
			"type": "arrow",
			"x": 2072.095606729543,
			"y": -1037.0084686544087,
			"width": 971.4285714285716,
			"height": 1417.142857142857,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1451503845,
			"version": 281,
			"versionNonce": 1515334763,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1703163732076,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					288.57142857142844,
					-211.42857142857156
				],
				[
					574.2857142857147,
					142.85714285714278
				],
				[
					82.85714285714312,
					431.42857142857133
				],
				[
					971.4285714285716,
					688.5714285714284
				],
				[
					302.8571428571431,
					1108.5714285714284
				],
				[
					400,
					1205.7142857142856
				]
			],
			"lastCommittedPoint": [
				400,
				1205.7142857142856
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "yhu2zXBdNxj4lZxx9RIva",
			"type": "arrow",
			"x": 3064.925896851986,
			"y": -1017.008468654409,
			"width": 971.428571428572,
			"height": 1417.1428571428578,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 2095983941,
			"version": 282,
			"versionNonce": 1283810245,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1703163732076,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-288.57142857142856,
					-211.42857142857164
				],
				[
					-574.2857142857149,
					142.85714285714283
				],
				[
					-82.85714285714316,
					431.4285714285715
				],
				[
					-971.428571428572,
					688.5714285714288
				],
				[
					-302.85714285714323,
					1108.571428571429
				],
				[
					-400.00000000000017,
					1205.714285714286
				]
			],
			"lastCommittedPoint": [
				400,
				1205.7142857142856
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "DST-jBiRfvn64O5RWSfR2",
			"type": "arrow",
			"x": 2082.095606729543,
			"y": -34.99763190684973,
			"width": 971.4285714285716,
			"height": 1417.142857142857,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1007923685,
			"version": 283,
			"versionNonce": 277788037,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1703163727260,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					288.57142857142844,
					211.42857142857156
				],
				[
					574.2857142857147,
					-142.85714285714278
				],
				[
					82.85714285714312,
					-431.42857142857133
				],
				[
					971.4285714285716,
					-688.5714285714284
				],
				[
					302.8571428571431,
					-1108.5714285714284
				],
				[
					400,
					-1205.7142857142856
				]
			],
			"lastCommittedPoint": [
				400,
				1205.7142857142856
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1390.7615361275996,
		"scrollY": 1608.5263257972658,
		"zoom": {
			"value": 0.35000000000000003
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%