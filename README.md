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
| 事件名称 | 事件大类 | 事件槽位 |
| :--- | :---| :---| 
|deploy.v|Arranging|Agent;Theme;Time;Configuration;Manner;Location;Circumstances;Purpose;Instrument;Means;Degree|
|depose.v|Change_of_leadership|Selector;Old_leader;New_leader;Role;Old_order;Degree;Depictive;Manner;Means;Result;Circumstances;Function;Time;Place;Body|
|deposit.v|Placing|Agent;Theme;Source;Path;Goal;Manner;Degree;Depictive;Means;Result;Duration;Place;Explanation;Time;Area;Cotheme;Distance;Speed;Cause;Purpose;Beneficiary|
|deprecate.v|Judgment_communication|Addressee;Communicator;Medium;Topic;Degree;Evaluee;Expressor;Manner;Means;Reason;Role;Result;Depictive;Grounds;Extent_of_acclaim;Time;Place;Internal_cause;Frequency|
|depress.v|Experiencer_obj|Experiencer;Stimulus;Degree;Depictive;Manner;Means;Result;Circumstances;Explanation;Time|
|deprive.v|Prevent_or_allow_possession|Potential_hindrance;State_of_affairs;Time;Place;Agent;Protagonist;Purpose;Duration;Explanation;Frequency;Containing_event|
|derail.v|Thwarting|Preventing_cause;Protagonist;Action;Time;Place;Manner;Degree;Explanation;Frequency|
|deride.v|Judgment_communication|Addressee;Communicator;Medium;Topic;Degree;Evaluee;Expressor;Manner;Means;Reason;Role;Result;Depictive;Grounds;Extent_of_acclaim;Time;Place;Internal_cause;Frequency|
|descale.v|Emptying|Agent;Theme;Source;Path;Goal;Degree;Depictive;Manner;Means;Result;Instrument;Cause;Place;Time;Containing_event;Explanation;Circumstances;Purpose|
|descend (on).v|Arriving|Theme;Source;Path;Goal;Manner;Means;Mode_of_transportation;Cotheme;Time;New_situation;Depictive;Period_of_iterations;Circumstances;Purpose;Degree;Event_description;Re-encoding;Frequency;Place|
|descend.v|Motion_directional|Area;Depictive;Distance;Duration;Goal;Manner;Path;Speed;Time;Carrier;Theme;Source;Result;Place;Degree;Point_of_contact;Path_shape;Means;Direction;Explanation;Purpose;Circumstances|
|descend.v|Path_shape|Source;Path;Goal;Road;Manner;Distance;Area;Degree;Means;Result;Speed;Depictive;Place;Path_shape;Direction;Time;Purpose|
|descend.v|Traversing|Theme;Source;Path;Goal;Manner;Distance;Area;Degree;Means;Speed;Cotheme;Depictive;Place;Path_shape;Direction;Time;Purpose;Means_of_motion;Duration;Result;Explanation;Reciprocation;Containing_event;Frequency;Re-encoding;New_situation;Circumstances;Endpoints;Coordinated_event;Period_of_iterations;Event_description;Iterations|
|describe.v|Communicate_categorization|Speaker;Category;Item;Means;Medium;Time;Place;Circumstances;Criteria;Manner;Duration|
|describe.v|Statement|Speaker;Addressee;Message;Topic;Manner;Means;Internal_cause;Medium;Depictive;Time;Place;Occasion;Particular_iteration;Communicative_force;Degree;Group;Event_description;Frequency;Iterations;Containing_event|
|descry.v|Becoming_aware|Cognizer;Phenomenon;Ground;State;Evidence;Degree;Manner;Means;Topic;Time;Purpose;Instrument;Frequency;Circumstances;Explanation;Particular_iteration;Period_of_iterations|
|desert.v|Quitting_a_place|Self_mover;Source;Path;Intended_goal;Manner;Means;Speed;Co-participant;Depictive;Place;Path_shape;Direction;Time;Purpose;Vehicle;Duration_of_final_state;Result;Explanation;Reciprocation;Containing_event;Frequency;Re-encoding;New_situation;Circumstances;Coordinated_event;Distance|
|deserve.v|Deserving|State_of_affairs;Action;Degree;Domain;Circumstances|
|desiccate.v|Cause_to_be_dry|Agent;Dryee;Instrument;Manner;Means;Place;Purpose;Time;Cause;Subregion;Duration;Temperature;Degree|
|design.v|Coming_up_with|Cognizer;Idea;Purpose;Material;Amount_of_progress;Depictive;Manner;Means;Result;Location_of_appearance;Place;Time|
|designate.v|Appointing|Selector;Official;Role;Degree;Depictive;Manner;Means;Result;Circumstances;Function;Time;Place;Body|
|designate.v|Linguistic_meaning|Form;Meaning;Textual_location;Referent;Degree|
# 总结
1、本项目旨在收集、整理成目前开放的Schema数据集，用于指导知识图谱/事件构建。  
2、事件图谱与知识图谱schema的发现，是进行事件图谱建模的一个重要手段，也是十分核心的问题。  
