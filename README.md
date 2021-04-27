# SchemaKG
schemakg， a knowledge graph for schema that seeks to cover a range of things as much as possible including entity schema and event schema。试图构建起覆盖度尽可能广的schema体系，包括实体以及事件。

# 百度词条Schema(部分)

| 概念大类 | 概念小类 | 属性槽位 |
| :--- | :---: | :--- |
|生活|火车站|name-中文名		foreignName-外文名		railwayStationCode-车站代码		dateOfOpening-投用日期		affiliatedRegion-所属地区		railwayStationGrade-车站等级		majorRailway-主要线路		administration-区域管理		constructionArea-建筑面积		numberOfPlatforms-站台规模		annualPassengerThroughput-年客运量		annualCargoThroughput-年货运量		address-车站地址|
|地理|森林公园|name-中文名		forestParkGrade-森林公园级别		affiliatedRegion-地理区域		address-地理位置		area-面积		climaticZone-气候带		vegetationType-植被类型		competentAuthority-管理单位		dateOfApproval-批准时间		approvalNumber-批准文号|
|社会|电视台频道|name-中文名		foreignName-外文名		alternateName-别称		type-类型		dateOfEstablishment-成立时间		majorProgram-代表节目		language-语言|
|历史|年代|name-中文名		foreignName-外文名		alternateName-别名		timeRange-时间范围|
|人物|历史人物|name-本名		alternateName-别名		courtesyName-字		pseudonym-号		era-所处时代		ethnicGroup-民族族群		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		majorWorks-主要作品		majorAchievement-主要成就|
|科技|化学品|name-中文名		foreignName-外文名		alternateName-别名		chemicalFormula-化学式		molecularWeight-分子量		casNumber-CAS登录号		einecsNumber-EINECS登录号		meltingPoint-熔点		boilingPoint-沸点		waterSolubility-水溶性		density-密度		appearance-外观		flashingPoint-闪点		application-应用		securityDescription-安全性描述		hazardSymbol-危险性符号		hazardDescription-危险性描述		unNumber-UN危险货物编号		cnNumber-CN危险货物编号|
|人物|话题人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		occupation-职业|
|娱乐|轻小说|name-中文名		originalName-原版名称		alternateName-别名		original-原作		author-作者		Illustrator-插画		translator-译者		type-类型		region-地区		magazine-连载杂志		firstIssueNumber-揭载号		originalRun-连载期间		publisher-出版社		affiliatedLibrary-所属文库		bookSeries-丛书系列		originalRelease-出版期间		numberOfPublications-刊行册数		dateOfPublication-出版时间		isbn-ISBN		bookDesign-装帧		bookSize-开本		numberOfPages-页数		price-定价		otherPublishers-其他出版社|
|文化|其他文化|name-中文名		foreignName-外文名		alternateName-别名|
|社会|科研机构|name-中文名		foreignName-外文名		dateOfEstablishment-成立时间		address-机构地址		competentAuthority-主管部门|
|娱乐|演出|name-中文名		foreignName-外文名		time-演出时间		location-演出地点		type-类型		starring-主演|
|文化|虚拟事物|name-中文名		foreignName-外文名		source-出处		type-类型|
|地理|现代建筑|name-中文名		foreignName-外文名		address-地理位置		floorArea-占地面积		dateOfOpening-投用时间		openingHours-开放时间|
|文化|戏剧表演作品|name-中文名		dateOfRelease-首演时间		type-类型|
|科技|定理定律|name-中文名		foreignName-外文名		alternateName-别名		expression-表达式		proposer-提出者		dateOfProposal-提出时间		fieldOfUse-适用领域|
|生活|民用机场|name-中文名		foreignName-外文名		icaoCode-ICAO代码		iataCode-IATA代码		dateOfOpening-通航日期		affiliatedRegion-所属地区		aerodromeRefCode-飞行区等级		airportType-机场类型		administration-地区管理		terminalArea-航站楼面积		numberOfParkingBays-机位数量		runwayLength-跑道长度		numberOfAirlines-航线数量		numberOfDestinations-通航城市		annualPassengerThroughput-旅客吞吐量		annualCargoThroughput-货邮吞吐量		aircraftMovements-起降架次		operatingOrganization-运营机构|
|地理|科技馆/博物馆|name-中文名		foreignName-外文名		address-地理位置		floorArea-占地面积		category-类别		scenicLevel-景点级别		dateOfOpening-投用时间		openingHours-开放时间		entranceTicketPrice-门票价格|
|社会|政府机构|name-中文名		foreignName-外文名		dateOfEstablishment-成立时间		address-办公地址		institutionType-性质		administrativeLevel-行政级别|
|生活|隧道|name-中文名		foreignName-外文名		dateOfCommencement-开工时间		status-投用状态		affiliatedRegion-所属地区		length-长度		width-宽度		constructionUnit-建设单位|
|艺术|电影作品|name-中文名		foreignName-外文名		alternateName-其他译名		type-类型		presenterCompany-出品公司		producerRegion-制片地区		dateOfShooting-拍摄日期		filmingLocation-拍摄地点		publisherCompany-发行公司		director-导演		scriptwriter-编剧		producer-制片人		starring-主演		runningTime-片长		dateOfRelease-上映时间		boxOffice-票房		language-对白语言		color-色彩		grade-电影分级		imdbCode-imdb编码		majorPrize-主要奖项		onlinePlayingPlatform-在线播放平台|
|人物|医疗人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		nativePlace-籍贯		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		academicDegree-学历		teachingTitle-教学职称		clinicalTitle-临床职称		placeOfPractice-执业地点|
|人物|音乐人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		zodiac-星座		bloodType-血型		bodyHeight-身高		bodyWeight-体重		graduatedFrom-毕业院校		occupation-职业		agency-经纪公司		majorWorks-代表作品		majorAchievement-主要成就|
|艺术|单曲|name-中文名		foreignName-外文名		album-所属专辑		duration-歌曲时长		originalSinger-歌曲原唱		lyricist-填词		composer-谱曲		arranger-编曲		genre-音乐风格		dateOfPublication-发行日期		language-歌曲语言|
|文化|期刊|name-中文名		foreignName-外文名		language-语种		category-类别		competentAuthority-主管单位		organizer-主办单位		editingOrganization-编辑单位		dateOfPublication-创刊时间		frequency-出版周期		cnsn-国内刊号		issn-国际刊号		postalCode-邮发代号		price-定价|
|社会|武器装备|name-中文名		foreignName-外文名		antetype-前型/级		subtype-次型/级		manufacturer-研制单位		dateOfDevelopment-研制时间		serviceTime-服役时间		dateOfCompletion-定型时间		affilliatedCountry-国家|
|自然|其他自然|name-中文名		foreignName-外文名		alternateName-别名|
|文化|文化活动|name-中文名		foreignName-外文名		time-时间		location-地点|
|生活|城市公交系统|name-中文名		foreignName-外文名		busType-公交类型		affiliatedRegion-所属地区		fleetSize-车队规模		lineLength-线网长度		numberOfStations-车站数量		averageDailyPassengerThroughput-日均客运量		maximumDailyPassengerThroughput-日最高客运量		annualPassengerThroughput-年客运量		broadcastingLanguage-报站语言		ticketPrice-车票价格		regulation-管理规章		operatingOrganization-运营机构|
|社会|社会事件|name-中文名		foreignName-外文名		time-发生时间		location-发生地点|
|科技|疾病症状|name-中医病名		foreignName-外文名		alternateName-别名		clinicalDepartment-就诊科室		susceptiblePopulation-多发群体		diseaseSite-常见发病部位		cause-常见病因		symptom-常见症状		infectivity-传染性		routeOfTransmission-传播途径|
|自然|自然资源|name-中文名		foreignName-外文名		purpose-用途		classification-分类|
|体育|体育术语|name-中文名		foreignName-外文名		definition-定义		sports-所属运动|
|艺术|漫画作品|name-中文名		originalName-原版名称		alternateName-别名		author-作者		type-类型		original-原作者		originalWork-原作品		translator-译者		scriptwriter-剧本		painter-作画		region-地区		magazine-连载杂志		firstIssueNumber-揭载号		originalRun-连载期间		bookSeries-丛书系列		originalRelease-出版期间		numberOfVolumes-单行本册数		publisher-出版社		dateOfPublication-出版时间		numberOfPages-页数		price-定价		bookSize-开本		bookDesign-装帧		isbn-ISBN|
|生活|营业场所|name-中文名		foreignName-外文名		businessHours-开业时间		address-地理位置|
|人物|政治人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		nativePlace-籍贯		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		jobTitle-职务		politicalAffiliation-政治面貌		majorWorks-代表作品|
|科技|软件|name-软件名称		platform-软件平台		dateOfRelease-上线时间		dateOfLatestUpdate-最近更新时间		developingLanguage-软件语言		developer-开发商		licensingMethod-软件授权		latestVersion-软件版本		softwareSize-软件大小|
|人物|明星组合|name-中文名		foreignName-外文名		member-组合成员		dateOfEstablishment-成立时间		agency-经纪公司		majorWorks-代表作品|
|科技|仪器设备|name-中文名		foreignName-外文名		purpose-用途|
|社会|学科专业|name-中文名		foreignName-外文名		dateOfEstablishment-创办时间		category-类别		competentAuthority-主管部门|
|艺术|演出|name-中文名		foreignName-外文名		time-演出时间		location-演出地点		type-类型		starring-主演|
|文化|网络热词|name-中文名		foreignName-外文名		definition-含义		timeOfPopularity-流行时间|
|自然|植物|name-中文名		latinName-拉丁学名		alternateName-别名		kingdom-界		subkingdom-亚界		superphylum-总门		phylum-门		subphylum-亚门		class-纲		subclass-亚纲		superorder-超目		order-目		suborder-亚目		family-科		subfamily-亚科		tribe-族		subtribe-亚族		genus-属		subgenus-亚属		group-组		subgroup-亚组		species-种		subspecies-亚种		variety-变种		varieties-品种		distributionArea-分布区域		namedBy-命名者及年代		protectionLevel-保护级别|
|文化|文物|name-中文名		foreignName-外文名		address-馆藏地点		unearthedTime-出土时间		era-所属年代		category-类别|

# Framenet Schema（部分）
| 事件名称 | 事件槽位 |
| :--- | :---| 
|Abandonment|Agent;Theme;Place;Time;Manner;Duration;Explanation;Depictive;Degree;Means;Purpose;Event_description
|Abounding_with|Theme;Location;Degree;Depictive;Time|
|Absorb_heat|Entity;Container;Heat_source;Place;Medium;Manner;Time;Explanation;Temperature;Duration;Circumstances;Purpose;Depictive;Result|
|Abundance|Collection;Quantity;Degree;Time;Circumstances;Measure;Place|
|Abusing|Abuser;Victim;Type;Degree;Place;Time;Manner;Means;Instrument;Purpose;Explanation;Duration;Frequency;Depictive;Circumstances;Period_of_iterations|
|Access_scenario|Theme;Useful_location;Barrier|
|Accompaniment|Participant;Co-participant;Participants|
|Accomplishment|Means;Agent;Instrument;Place;Time;Manner;Explanation;Degree;Goal;Outcome;Circumstances;Duration;Domain;Particular_iteration|
|Accoutrements|Wearer;Style;Material;Accoutrement;Descriptor;Use;Part;Body_location;Creator;Time_of_creation;Name|
|Accuracy|Agent;Target;Outcome;Means;Degree;Time;Place;Instrument;Target_value;Deviation;Domain;Circumstances;Frequency|
|Achieving_first|Cognizer;New_idea;Time;Place;Means;Purpose;Explanation;Field;Instrument;Manner;Basis;Location_of_appearance|
|Active_substance|Effect;Substance;Descriptor;Type;Name|
|Activity|Activity;Duration;Place;Time;Agent;Manner|
|Activity_abandoned_state|Agent;Time;Duration;Activity;Place|
|Activity_done_state|Agent;Activity;Time;Place|
|Activity_finish|Depictive;Manner;Result;Co-timed_event;Place;Time;Agent;Activity;Means;Purpose;Degree;Explanation;Circumstances;Containing_event|
|Activity_ongoing|Duration;Activity;Place;Purpose;Time;Depictive;Manner;Means;Co-timed_event;Agent;Explanation;Event_description;Circumstances|
|Activity_pause|Activity;Agent;Manner;Means;Place;Time;Purpose;Depictive;Completeness;Duration;Legal_basis;Explanation;Event_description|
|Activity_paused_state|Agent;Time;Activity;Duration|
|Activity_prepare|Agent;Activity;Place;Time;Manner;Means;Purpose;Duration;Depictive;Degree;Beneficiary;Iterations;Event_description|
|Activity_ready_state|Protagonist;Activity;Salient_entity;Time;Result;Duration;Degree|
|Activity_resume|Duration;Activity;Place;Explanation;Time;Manner;Agent;Circumstances;Depictive;Result;Event_description|
|Activity_start|Place;Purpose;Time;Depictive;Manner;Means;Activity;Agent;Co-timed_event;Circumstances;Containing_event;Event_description;Explanation;Particular_iteration;New_situation;Communicative_force;Concessive|
|Activity_stop|Purpose;Place;Time;Depictive;Manner;Result;Agent;Activity;Duration;Means;Co-timed_event;Degree;Frequency;Containing_event;Circumstances;Re-encoding;Explanation;Event_description;Particular_iteration|
|Actually_occurring_entity|Instance;Type
|Addiction|Addict;Addictant;Degree;Compeller|
|Adding_up|Cognizer;Numbers;Result;Time;Place;Purpose;Means;Manner|
|Adducing|Speaker;Addressee;Manner;Means;Medium;Depictive;Time;Place;Specified_entity;Role;Purpose;Explanation;Containing_event;Event_description;Frequency;Circumstances|
|Adjacency|Ground;Figure;Distance;Direction;Time;Figures;Deixis;Accessibility;Directness|
|Adjusting|Agent;Part;Feature;Imposed_purpose;Means;Place;Time;Final_value;Instrument;Purpose;Manner;Degree;Circumstances|
|Adopt_selection|Agent;Attribute;Value;Time;Manner;Event_description;Depictive;Purpose;Role;Place;Frequency;Containing_event;Circumstances;Re-encoding;Particular_iteration;Means;Instrument;Duration;Explanation;Communicative_force|
|Aesthetics|Entity;Attribute;Degree;Time;Circumstances;Viewpoint;Place|
|Affirm_or_deny|Speaker;Message;Addressee;Place;Time;Manner;Iterations;Means;Depictive;Degree;Containing_event;Event_description;Frequency;Internal_cause;Medium;Topic|
|Age|Entity;Attribute;Age;Degree;Time;Circumstances;Expressor;Descriptor;Duration|
|Aggregate|Individuals;Aggregate;Aggregate_property;Name;Container_possessor;Domain|
|Aging|Entity;Time;Circumstances;Manner;Place;Result|
|Agree_or_refuse_to_act|Speaker;Interlocutor;Medium;Proposed_action;Manner;Depictive;Means;Internal_cause;Place;Time;Purpose;Particular_iteration;Role;Co-timed_event;Frequency;Explanat|ion;Event_description|
|Agriculture|Agriculturist;Food;Instrument;Duration;Manner;Means;Outcome;Place;Time;Purpose;Frequency;Degree;Ground;Particular_iteration;Type;Event_description;Circumstances|
|Aiming|Agent;Targeted;Outcome;Means;Time;Depictive;Place;Manner;Duration;Purpose;Particular_iteration;Circumstances;Instrument;Target_location;Location_of_protagonist;Activity;Containing_event;Explanation|
|Alignment_image_schema|Alignment_match;Ground;Alignment_mismatch|
|Alliance|Alliance;Members;Purpose;Period_of_existence;Member_1;Member_2;Descriptor|
|Alternatives|Situation;Agent;Number_of_possibilities;Salient_entity;Purpose|
|Alternativity|Profiled_alternative;Contrasting_alternative|
|Amalgamation|Parts;Whole;Part_1;Part_2;Degree;Manner;Result;Time;Place;Depictive;Descriptor|
|Amassing|Recipient;Mass_theme;Source;Place;Purpose;Explanation;Time;Means;Manner;Result;Duration;Circumstances;Role|
|Ambient_temperature|Place;Attribute;Temperature;Degree;Time;Circumstances;Weather|
|Ammunition|Ammunition;Use;Creator;Time_of_creation;Name;Type;Material;Weapon|
|Amounting_to|Value;Attribute;Time_span;Frequency;Numbers|
|Animals|Animal;Descriptor;Origin;Characteristic|
|Annoyance|Experiencer;Topic;Stimulus;Degree;Empathy_target;Expressor;Explanation;Circumstances;State;Parameter;Manner;Time|
# 总结
本项目旨在收集、整理成目前开放的Schema数据集，用于指导知识图谱构建。
