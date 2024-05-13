links:: [Local library](zotero://select/groups/2386895/items/GNR9MLAH), [Web library](https://www.zotero.org/groups/2386895/items/GNR9MLAH)
authors:: [[Hervé Déjean]], [[Jean-Luc Meunier]], [[Liangcai Gao]], [[Yilun Huang]], [[Yu Fang]], [[Florian Kleber]], [[Eva-Maria Lang]]
date:: [[Apr 23rd, 2019]]
item-type:: [[dataset]]
title:: @ICDAR 2019 Competition on Table Detection and Recognition (cTDaR)

- [[Abstract]]
	- The aim of this competition is to evaluate the performance of state of the art methods for table detection (TRACK A) and table recognition (TRACK B). For the first track, document images containing one or several tables are provided. For TRACK B two subtracks exist: the first subtrack (B.1) provides the table region. Thus, only the table structure recognition must be performed. The second subtrack (B.2) provides no a-priori information. This means, the table region and table structure detection has to be done. The Ground Truth is provided in a similar format as for the ICDAR 2013 competition (see [2]): <?xml version="1.0" encoding="UTF-8"?> <document filename='filename.jpg'>     <table id='Table_1540517170416_3'>          <Coords points="180,160 4354,160 4354,3287 180,3287"/>        <cell id='TableCell_1540517477147_58' start-row='0' start-col='0' end-row='1' end-col='2'>            <Coords points="180,160 177,456 614,456 615,163"/>        </cell>         ...     </table>     ... </document>   The difference to Gobel et al. [2] is the Coords tag which defines a table/cell as a polygon specified by a list of coordinates. For B.1 the table and its coordinates is given together with the input image. Important Note: For the modern dataset, the convex hull of the content describes a cell region. For the historical dataset, it is requested that the output region of a cell is the cell boundary. This is necessary due to the characteristics of handwritten text, which is often overlapping with different cells. See also: http://sac.founderit.com/tasks.html The evaluation tool is available at github: https://github.com/cndplab-founder/ctdar_measurement_tool
- [[Attachments]]
	- [Zenodo Snapshot](https://zenodo.org/record/3239032#.X1IyZdbgqrI) {{zotero-imported-file 4X34SPQX, "3239032.html"}}
- [[Notes]]
	- http://sac.founderit.com/