

# DML Hong Kong Culture Map (IMD)

Dataset of DML Hong Kong Culture Map (IMD)
|	Field Name	|	Mandatory / Optional	|	Remarks	|	Examples	|
|	---	|	---	|	---	|	---	|
|	id	|	M	|	An 3 letters - 6 digits	unique identifier |	TUP-000001	|
|	isPost	|	*(Input by LIB)*	|	Y or N - display (or not) in gateway	|		|
|	owner	|	*(Input by LIB)*	|	Use controlled vocabulary	|	DIR / SCA / MCAT / CML	|
| department | M | Unit or dept to which this item belongs - use names from [HKBU Website](https://www.hkbu.edu.hk/en/about/faculties.html) | Institute of Transdisciplinary Studies |
|	digital_object_type	|	*(Input by LIB)*	|	Use [AAT vocabularies](https://www.getty.edu/research/tools/vocabularies/aat/index.html)	|	digital images;streaming video;digital documents |
|	work_type	|	*(Input by LIB)*	|	Use [AAT vocabularies](https://www.getty.edu/research/tools/vocabularies/aat/index.html)	| works of art;musical performance	|
|		|		|		|		|
|	dataset_name_en	|	M (en or zh)<br>*(Input by LIB)*	|	Collection / Database / DSG project name - Free text	|	HKBU Heritage<br>Transdisciplinary UG Programmes	|
|	dataset_name_zh-Hant	|	M (en or zh)<br>*(Input by LIB)*	|	Free text	|		|
|	dataset_name_zh-Hans	|	M (en or zh)<br>*(Input by LIB)*	|	Free text	|		|
|	title_en	|	M (en or zh)	|	Free text<br /><br />Default value: blank (not NULL)	|		|
|	title_zh-Hant	|	M (en or zh)	|	Free text<br /><br />Default value: blank (not NULL)	|		|
|	title_zh-Hans	|	M (en or zh)<br>*(Input by LIB)*	|	Free text<br /><br />Default value: blank (not NULL)	|		|
|	*sort_group_en*	|	*(Input by LIB)*	|		|		|
|	*sort_en*	|	*(Input by LIB)*	|		|		|
|	*sort_group_zh*	|	*(Input by LIB)*	|		|		|
|	*sort_zh-Hant*	|	*(Input by LIB)*	|		|		|
|	*sort_zh-Hans*	|	*(Input by LIB)*	|		|		|
|	authors_en	|	O	|	Free text<br /><br />Default value: NULL<br /><br />Delimiter: ';'	| SUEN, Chun Fung;Suen, Chun Fung;Suen Chun Fung;S.F. Suen |
|	authors_zh-Hant	|	O	|	Free text<br /><br />Default value: NULL<br /><br />Delimiter: ';'	| 孫振鋒;陳志芬 |
|	authors_zh-Hans	|	O<br>*(Input by LIB)*	|	Free text<br /><br />Default value: NULL<br /><br />Delimiter: ';'	| 孙振锋;陈志芬 |
|	abstract_en	|	O	|	Free text<br /><br />Default value: NULL |		|
|	abstract_zh-Hant	|	O	|	Free text<br /><br />Default value: NULL |		|
|	abstract_zh-Hans	|	O<br>*(Input by LIB)*	|	Free text<br /><br />Default value: NULL |		|
|	keywords_en	|	O	|	Free text<br /><br />Default value: NULL<br /><br />Delimiter: ';'	|	film;student productions;animations	|
|	keywords_zh-Hant	|	O	|	Free text<br /><br />Default value: NULL<br /><br />Delimiter: ';'	| 電影;學生作品;動畫 |
|	keywords_zh-Hans	|	O<br>*(Input by LIB)*	|	Free text<br /><br />Default value: NULL<br /><br />Delimiter: ';'	| 电影;学生作品;动画 |
|	date_yyyy	|	O	|	Number (published year)<br /><br />Default value: NULL	|	1945	|
|	date_mm	|	O	|	Number (published month)<br /><br />Default value: NULL	|	3	|
|	date_dd	|	O	|	Number	(published day)<br /><br />Default value: NULL |	12	|
|	date_certainty	|	O	|	Use controlled vocabulary<br /><br />Default value: NULL	|	century *(for records from 19xx, you should input 1900 in the field date_yyyy)*<br>decade *(for records from 198x, you should input 1980 in the field date_yyyy)*	|
|	issue	|	O	|	For any periodical issue / volume number or text - Free text<br /><br />Default value: NULL	|	12(3) <br>Vol. 3<br>Special Issue	|
|	*no_date* | *(Input by LIB)*	|	Default value: NULL	|		|
|	format	|	O	|	Size / format specification of the physical object being digitized - Free text<br /><br />Default value: NULL	|		1 hanging scroll : ink on paper ; image 66 x 59 cm., mount 178 x 68 cm.	|
|	language	|	O	|	Use [IETF Language tag](https://en.wikipedia.org/wiki/IETF_language_tag) (delimited)<br /><br />Default value: NULL	|	en;zh-Hans;zh-Hant	|
|	ocr_text	|	O<br>*(Input by LIB)*	|	Y or N	|	 |
|	publisher_en	|	O	|	Free text<br /><br />Default value: NULL	|		|
|	publisher_zh-Hant	|	O	|	Free text<br /><br />Default value: NULL	|		|
|	publisher_zh-Hans	|	O<br>*(Input by LIB)*	|	Free text<br /><br />Default value: NULL	|		|
|	published_in_en	|	O	|	Free text<br /><br />Default value: NULL	|		|
|	published_in_zh-Hant	|	O	|	Free text<br /><br />Default value: NULL	|		|
|	published_in_zh-Hans	|	O<br>*(Input by LIB)*	|	Free text<br /><br />Default value: NULL	|		|
|	acknowledgement_en	|	O	|	Free text<br /><br />Default value: NULL	| XXVII International VGIK Student Festival 2007 [Finalist];RTHK TV Programme Commissioning 2007 [Selected Film for Animation Category] |
|	acknowledgement_zh-Hant	|	O	|	Free text<br /><br />Default value: NULL	| 第二十七屆莫斯科電影學院國際學生電影獎 2007「入圍作品」;香港電台電視節目外判計劃 2007 「精選動畫影片」 |
|	acknowledgement_zh-Hans	|	O<br>*(Input by LIB)*	|	Free text<br /><br />Default value: NULL	| 第二十七届莫斯科电影学院国际学生电影奖 2007「入围作品」;香港电台电视节目外判计划 2007 「精选动画影片」 |
|		|		|		|		|
|	url_storage_path	|	O<br>*(Input by LIB)*	|	Full URL<br /><br />Default value: NULL	|	https://storage.lib.hkbu.edu.hk/projects/sys/	|
|	url_storage_filename	|	O	|	filename<br /><br />Default value: NULL<br /><br />Delimiter: ';' |	TUP-000001_01.jpg;TUP-000001_02.jpg	|
|	url_permalink	|	M<br>*(Input by LIB)*	|	Full URL 	| https://digital.lib.hkbu.edu.hk/sys/record.php	|
|	url_thumbnail	|	M<br>*(Input by LIB)*	|	Full URL	|	https://digital.lib.hkbu.edu.hk/sys/thumbnail_001.jpg		|
|	wikidata	|	O<br>*(Input by LIB)*	|	Only the Q-number<br /><br />Default value: NULL	|	Q23432	|
|		|		|		|		|
|	copyright status	|	O	|	Use [LC vocabulary](https://id.loc.gov/vocabulary/preservation/copyrightStatus.html)	|	copyrighted <br>public domain <br>unknown	|
|	copyright notes	|	O	|	Free text<br /><br />Default value: NULL	|		|
|	copyright end date	|	O	|	YYYY-MM-DD<br /><br />Default value: NULL	|	2025-01-01	|
|	license	|	O	|	Use controlled vocabulary	|	open access <br>IP control <br>hkbu only <br>CC BY <br>CC BY-SA <br>CC BY-NC 4.0|
|	license_notes	|	O	|	Free text<br /><br />Default value: NULL	|		|
|	license_end_date	|	O	|	YYYY-MM-DD<br /><br />Default value: NULL	|	2025-01-01	|
