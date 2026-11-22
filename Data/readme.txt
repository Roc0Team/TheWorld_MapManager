* A server can manage a single map in its life-cycle

* Map data are pointed by TheWorld_MapManager.json which must be copied in the GDExtension bin directory (a copy is Data\_must_be_copied_in_the_bin_folder_as_TheWorld_MapManager.json)

* To set e new map:
  - update Data\DBJson.json: the dir name and the conf file name of the new map
  - create the file referenced in the previous line otherwise it will be created with default values  '{"MapName" : "TestMap04", "GrowingBlockVertexNumberShift" : "8", "GridStepInWU" : "2.0", "HeightsFormatInQuadrantBuffer" : "UInt16"}'
  
 * To copy a map:
	- Set the correct name in Data\Conf\DBJson.json
	- Copy  DBJson\<nome_mappa>.json
	- Copy DBJson\maps\<nome_mappa>
	- Copy Cache\maps\<nome_mappa>
