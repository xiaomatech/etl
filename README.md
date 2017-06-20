
```

<property>
    <name>hive.aux.jars.path</name>
    <value>file:///opt/hive/jars/hive-third-functions-2.1.1-shaded.jar</value>
</property>

add jar /opt/hive/jars/hive-third-functions-2.1.1-shaded.jar
create temporary function array_contains as 'cc.shanruifeng.functions.array.UDFArrayContains';
create temporary function array_equals as 'cc.shanruifeng.functions.array.UDFArrayEquals';
create temporary function array_intersect as 'cc.shanruifeng.functions.array.UDFArrayIntersect';
create temporary function array_max as 'cc.shanruifeng.functions.array.UDFArrayMax';
create temporary function array_min as 'cc.shanruifeng.functions.array.UDFArrayMin';
create temporary function array_join as 'cc.shanruifeng.functions.array.UDFArrayJoin';
create temporary function array_distinct as 'cc.shanruifeng.functions.array.UDFArrayDistinct';
create temporary function array_position as 'cc.shanruifeng.functions.array.UDFArrayPosition';
create temporary function array_remove as 'cc.shanruifeng.functions.array.UDFArrayRemove';
create temporary function array_reverse as 'cc.shanruifeng.functions.array.UDFArrayReverse';
create temporary function array_sort as 'cc.shanruifeng.functions.array.UDFArraySort';
create temporary function array_concat as 'cc.shanruifeng.functions.array.UDFArrayConcat';
create temporary function array_value_count as 'cc.shanruifeng.functions.array.UDFArrayValueCount';
create temporary function array_slice as 'cc.shanruifeng.functions.array.UDFArraySlice';
create temporary function array_element_at as 'cc.shanruifeng.functions.array.UDFArrayElementAt';
create temporary function bit_count as 'cc.shanruifeng.functions.bitwise.UDFBitCount';
create temporary function bitwise_and as 'cc.shanruifeng.functions.bitwise.UDFBitwiseAnd';
create temporary function bitwise_not as 'cc.shanruifeng.functions.bitwise.UDFBitwiseNot';
create temporary function bitwise_or as 'cc.shanruifeng.functions.bitwise.UDFBitwiseOr';
create temporary function bitwise_xor as 'cc.shanruifeng.functions.bitwise.UDFBitwiseXor';
create temporary function map_build as 'cc.shanruifeng.functions.map.UDFMapBuild';
create temporary function map_concat as 'cc.shanruifeng.functions.map.UDFMapConcat';
create temporary function map_element_at as 'cc.shanruifeng.functions.map.UDFMapElementAt';
create temporary function map_equals as 'cc.shanruifeng.functions.map.UDFMapEquals';
create temporary function day_of_week as 'cc.shanruifeng.functions.date.UDFDayOfWeek';
create temporary function day_of_year as 'cc.shanruifeng.functions.date.UDFDayOfYear';
create temporary function type_of_day as 'cc.shanruifeng.functions.date.UDFTypeOfDay'; 
create temporary function zodiac_cn as 'cc.shanruifeng.functions.date.UDFZodiacSignCn';
create temporary function zodiac_en as 'cc.shanruifeng.functions.date.UDFZodiacSignEn';
create temporary function pinyin as 'cc.shanruifeng.functions.string.UDFChineseToPinYin';
create temporary function md5 as 'cc.shanruifeng.functions.string.UDFMd5';
create temporary function sha256 as 'cc.shanruifeng.functions.string.UDFSha256';
create temporary function json_array_get as 'cc.shanruifeng.functions.json.UDFJsonArrayGet';
create temporary function json_array_length as 'cc.shanruifeng.functions.json.UDFJsonArrayLength';
create temporary function json_array_extract as 'cc.shanruifeng.functions.json.UDFJsonArrayExtract';
create temporary function json_array_extract_scalar as 'cc.shanruifeng.functions.json.UDFJsonArrayExtractScalar';
create temporary function json_extract as 'cc.shanruifeng.functions.json.UDFJsonExtract';
create temporary function json_extract_scalar as 'cc.shanruifeng.functions.json.UDFJsonExtractScalar';
create temporary function json_size as 'cc.shanruifeng.functions.json.UDFJsonSize';
create temporary function id_card_province as 'cc.shanruifeng.functions.card.UDFChinaIdCardProvince';
create temporary function id_card_city as 'cc.shanruifeng.functions.card.UDFChinaIdCardCity';
create temporary function id_card_area as 'cc.shanruifeng.functions.card.UDFChinaIdCardArea';
create temporary function id_card_birthday as 'cc.shanruifeng.functions.card.UDFChinaIdCardBirthday';
create temporary function id_card_gender as 'cc.shanruifeng.functions.card.UDFChinaIdCardGender';
create temporary function is_valid_id_card as 'cc.shanruifeng.functions.card.UDFChinaIdCardValid';
create temporary function id_card_info as 'cc.shanruifeng.functions.card.UDFChinaIdCardInfo';
create temporary function wgs_distance as 'cc.shanruifeng.functions.geo.UDFGeoWgsDistance';
create temporary function gcj_to_bd as 'cc.shanruifeng.functions.geo.UDFGeoGcjToBd';
create temporary function bd_to_gcj as 'cc.shanruifeng.functions.geo.UDFGeoBdToGcj';
create temporary function wgs_to_gcj as 'cc.shanruifeng.functions.geo.UDFGeoWgsToGcj';
create temporary function gcj_to_wgs as 'cc.shanruifeng.functions.geo.UDFGeoGcjToWgs';
create temporary function gcj_extract_wgs as 'cc.shanruifeng.functions.geo.UDFGeoGcjExtractWgs';
create temporary function url_encode as 'cc.shanruifeng.functions.url.UDFUrlEncode';
create temporary function url_decode as 'cc.shanruifeng.functions.url.UDFUrlDecode';
```