# SchemaKG
schemakg， a knowledge graph for schema that seeks to cover a range of things as much as possible including entity schema and event schema。试图构建起覆盖度尽可能广的schema体系，包括实体以及事件。

# 百度词条Schema 

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
|文化|文学作品|name-作品名称		foreignName-外文名		alternateName-作品别名		author-作者		era-创作年代		source-作品出处		genre-文学体裁|
|生活|菜品|name-中文名		foreignName-外文名		classification-分类		flavor-口味|
|生活|饮料|name-中文名		foreignName-外文名		alternateName-别名		majorIngredient-主要用料		flavor-口味|
|娱乐|电视节目|name-中文名		foreignName-外文名		alternateName-别名		country-国家/地区		type-类型		host-主持人		majorGuest-主要嘉宾		productionCompany-制作公司		dateOfRelease-首播时间		broadcastChannel-播出频道		broadcastingTime-播出时间		director-导演		runningTime-每集长度		broadcastingStatus-播出状态		onlinePlayingPlatform-在线播放平台|
|社会|图书馆|name-中文名		foreignName-外文名		abbreviation-简称		competentAuthority-主管部门		libraryType-馆舍类型		dateOfEstablishment-建馆时间		address-地址|
|文化|文具|name-中文名		foreignName-外文名		purpose-用途|
|人物|文化人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		occupation-职业		majorWorks-代表作品		majorAchievement-主要成就|
|科技|保健品|name-中文名		foreignName-外文名		approvalNumber-批准文号|
|科技|定义概念|name-中文名		foreignName-外文名		fieldOfUse-适用领域		affiliatedSubject-所属学科|
|地理|行政区划|name-中文名		foreignName-外文名		alternateName-别名		administrativeDivisionCode-行政区划代码		administrativeDivisionType-行政区类别		affiliatedRegion-所属地区		address-地理位置		area-面积		subdivision-下辖地区		municipalSeat-政府驻地		callingCode-电话区号		zipCode-邮政区码		climate-气候条件		population-人口数量		famousScenicSpot-著名景点		airport-机场		railwayStation-火车站		licensePlatePrefix-车牌代码		gdp-地区生产总值|
|地理|岛屿湖泊|name-中文名		foreignName-外文名		address-地理位置		area-面积|
|艺术|纯音乐|name-中文名		foreignName-外文名		alternateName-作品别名		genre-音乐风格		dateOfEstablishment-创作时间		composer-谱曲		dateOfRelease-首演时间		duration-音乐时长|
|其他|其他|name-中文名		foreignName-外文名		alternateName-别名|
|自然|自然现象|name-中文名		foreignName-外文名		alternateName-别名|
|生活|铁路线路|name-中文名		foreignName-外文名		dateOfOpening-开通日期		lineLength-线路长度		designSpeed-设计速度		operatingSpeed-运营速度		railwayGrade-铁路等级		terminal-起止站点|
|地理|国家|name-中文名		foreignName-外文名		abbreviation-简称		continent-所属洲		capital-首都		majorCity-主要城市		nationalDay-国庆日		nationalAnthem-国歌		countryCode-国家代码		officialLanguage-官方语言		currency-货币		timeZone-时区		politicalSystem-政治体制		nationalLeader-国家领袖		population-人口数量		populationDensity-人口密度		majorEthnicGroup-主要民族		majorReligion-主要宗教		territorialArea-国土面积		landArea-陆地面积		oceanArea-海洋面积		waterAreaRate-水域率		gdp-GDP总计		gdpPerCapita-人均GDP		internationalCallingCode-国际电话区号		internetTLD-国际域名缩写		drivingSide-道路通行|
|娱乐|电视剧作品|name-中文名		foreignName-外文名		alternateName-别名		type-类型		presenterCompany-出品公司		producerRegion-制片地区		filmingLocation-拍摄地点		publisherCompany-发行公司		dateOfRelease-首播时间		director-导演		scriptwriter-编剧		producer-制片人		starring-主演		numberOfEpisodes-集数		runningTime-每集长度		majorPrize-主要奖项		onlinePlayingPlatform-在线播放平台|
|自然|微生物|name-中文名		latinName-拉丁学名		alternateName-别名		kingdom-界		phylum-门		subphylum-亚门		class-纲		subclass-亚纲		order-目		suborder-亚目		family-科		subfamily-亚科		tribe-族		genus-属		subgenus-亚属		species-种		subspecies-亚种		distributionArea-分布区域|
|文化|小说作品|name-中文名		alternateName-别名		author-作者		type-类型		serialStatus-连载状态		serialPlatform-连载平台		latestChapter-最新章节		isPublished-是否出版		dateOfPublication-出版日期|
|社会|团队组织|name-中文名		foreignName-外文名		abbreviation-简称		competentAuthority-主管单位		registrationAuthority-登记单位		attribute-属性		address-社团地址		majorAchievement-主要成就|
|人物|虚拟人物|name-中文名		foreignName-外文名		alternateName-别名		portrayedBy-饰演		dubber-配音		gender-性别		debutWorks-登场作品		birthday-生日		age-年龄		virtualBloodType-虚拟人物血型		bodyHeight-身高		bodyWeight-体重		bwhMeasurements-三围|
|交通|隧道|name-中文名		foreignName-外文名		dateOfCommencement-开工时间		status-投用状态		affiliatedRegion-所属地区		length-长度		width-宽度		constructionUnit-建设单位|
|文化|书籍|name-书名		alternateName-别名		author-作者		category-类别		originalWork-原作品		translator-译者		publisher-出版社		dateOfPublication-出版时间		numberOfPages-页数		price-定价		bookSize-开本		bookDesign-装帧		isbn-ISBN|
|生活|城市轨道交通|name-中文名		foreignName-外文名		dateOfOpening-开通日期		railType-轨道类型		affiliatedRegion-所属地区		operationHours-运营时间		terminal-起止站点		operatingRoute-运营线路		lineLength-线路长度		numberOfStations-车站数量		averageDailyPassengerThroughput-日均客运量		maximumDailyPassengerThroughput-日最高客运量		annualPassengerThroughput-年客运量		broadcastingLanguage-报站语言		ticketPrice-车票价格		regulation-管理规章		operatingOrganization-运营机构|
|文化|文学体裁|name-中文名		alternateName-别名		numberOfWords-正文字数		timeOfEmergence-始兴年代|
|科技|手术|name-中文名		foreignName-外文名		operationType-专科分类|
|娱乐|电影作品|name-中文名		foreignName-外文名		alternateName-其他译名		type-类型		presenterCompany-出品公司		producerRegion-制片地区		dateOfShooting-拍摄日期		filmingLocation-拍摄地点		publisherCompany-发行公司		director-导演		scriptwriter-编剧		producer-制片人		starring-主演		runningTime-片长		dateOfRelease-上映时间		boxOffice-票房		language-对白语言		color-色彩		grade-电影分级		imdbCode-imdb编码		majorPrize-主要奖项		onlinePlayingPlatform-在线播放平台|
|生活|其他生活|name-中文名		foreignName-外文名		alternateName-别名|
|文化|节日|name-中文名		foreignName-外文名		alternateName-别名		holidayTime-节日时间		holidayType-节日类型		observedBy-流行地区		origin-节日起源		holidayActivity-节日活动		holidayFood-节日饮食		significance-节日意义		location-设定地点		foundingInstitution-设立机构		occurrenceCycle-设定时间|
|人物|体育人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		bodyHeight-身高		bodyWeight-体重		graduatedFrom-毕业院校		sports-运动项目		sportsTeam-所属运动队		professionalCharacteristics-专业特点		majorPrize-主要奖项		majorEvent-重要事件|
|文化|古代著作|name-书名		alternateName-别名		author-作者		category-类别		originalWork-原作品		translator-译者		publisher-出版社		dateOfPublication-出版时间		numberOfPages-页数		price-定价		bookSize-开本		bookDesign-装帧		isbn-ISBN|
|历史|历史机构|name-中文名		foreignName-外文名		dateOfEstablishment-成立时间		function-机构职能|
|地理|山脉|name-中文名		foreignName-外文名		alternateName-别名		mountainRange-所属山系		address-地理位置		trending-走向		length-长度		width-宽度		startPoint-起点		endPoint-终点		mainPeak-主峰		altitude-海拔|
|生活|交通工具|name-中文名		foreignName-外文名		powerSource-动力来源|
|人物|科学人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		occupation-职业		majorWorks-代表作品		majorAchievement-主要成就|
|人物|演员|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		zodiac-星座		bloodType-血型		bodyHeight-身高		bodyWeight-体重		graduatedFrom-毕业院校		occupation-职业		agency-经纪公司		majorWorks-代表作品		majorAchievement-主要成就|
|科技|电子产品|name-中文名		foreignName-外文名		dateOfRelease-上市时间		brand-所属品牌		productType-产品类型|
|社会|学校|name-中文名		foreignName-外文名		abbreviation-简称		dateOfEstablishment-创办时间		founder-创办人		schoolNature-办学性质		schoolType-学校类别		schoolCharacteristics-学校特色		competentAuthority-主管部门		affiliatedCompany-所属企业		president-现任领导		fullTimeAcademician-专职院士数		numberOfVocationalMajors-高职专业		numberOfUndergraduateMajors-本科专业		masterDegree-硕士点		doctorDegree-博士点		postdotoralDegree-博士后		nationalKeyDiscipline-国家重点学科		numberOfDepartments-院系设置		motto-校训		schoolSong-校歌		schoolDay-校庆日		departmentMotto-院训		departmentSong-院歌		departmentDay-院庆日		address-地址		collegeCode-院校代码		majorPrize-主要奖项		famousAlumni-知名校友		famousTeacher-知名教师|
|科技|工业产品|name-中文名		foreignName-外文名		dateOfRelease-上市时间		brand-所属品牌|
|娱乐|纯音乐|name-中文名		foreignName-外文名		alternateName-作品别名		genre-音乐风格		dateOfEstablishment-创作时间		composer-谱曲		dateOfRelease-首演时间		duration-音乐时长|
|生活|品牌|name-中文名		foreignName-外文名		industry-所属行业		dateOfEstablishment-创立时间		founder-创始人		affiliatedCompany-所属公司    |
|艺术|专辑|name-中文名		foreignName-外文名		language-专辑语言		singer-专辑歌手		duration-专辑时长		numberOfTracks-曲目数量		genre-音乐风格		recordCompany-唱片公司		dateOfPublication-发行日期		publishRegion-发行地区		sales-唱片销量		producer-制作人		majorPrize-获得奖项|
|历史|历史事件|name-中文名		foreignName-外文名		time-发生时间		location-发生地点		majorParticipant-主要人员|
|交通|城市公交线路|name-中文名		foreignName-外文名		dateOfOpening-开通日期		operationalStatus-运营状态		busType-公交类型		lineLength-线路长度		numberOfStations-车站数量		terminal-起止站点		firstAndLastTimeOfStartStation-起点首末班时间		firstAndLastTimeOfEndStation-终点首末班时间		ticketPrice-车票价格		operatingOrganization-运营机构|
|交通|城市轨道交通|name-中文名		foreignName-外文名		dateOfOpening-开通日期		railType-轨道类型		affiliatedRegion-所属地区		operationHours-运营时间		terminal-起止站点		operatingRoute-运营线路		lineLength-线路长度		numberOfStations-车站数量		averageDailyPassengerThroughput-日均客运量		maximumDailyPassengerThroughput-日最高客运量		annualPassengerThroughput-年客运量		broadcastingLanguage-报站语言		ticketPrice-车票价格		regulation-管理规章		operatingOrganization-运营机构|
|人物|电竞人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		occupation-职业		gameId-游戏ID		gameTeam-所属战队		gamePosition-游戏位置		majorAchievement-主要成就|
|科技|疗法|name-中文名		foreignName-外文名		clinicalDepartment-就诊科室|
|自然|动物|name-中文名		latinName-拉丁学名		alternateName-别名		kingdom-界		phylum-门		subphylum-亚门		class-纲		subclass-亚纲		order-目		suborder-亚目		family-科		subfamily-亚科		tribe-族		genus-属		subgenus-亚属		species-种		subspecies-亚种		distributionArea-分布区域		namedBy-命名者及年代		protectionLevel-保护级别|
|文化|传统技艺|name-中文名		foreignName-外文名		dateOfApproval-批准时间		heritageLevel-遗产级别		heritageType-遗产类别|
|文化|文化术语|name-中文名		foreignName-外文名		definition-定义|
|娱乐|游戏作品|name-中文名		originalName-原版名称		alternateName-别名		gameType-游戏类型		original-原作者		originalWork-原作品		platform-游戏平台		gameSeries-所属系列		region-地区		developer-开发商		publisherCompany-发行公司		dateOfPublication-发行日期		price-游戏售价		producer-制作人		director-总监		scriptwriter-编剧		majorDubber-主要配音		backgroundMusic-背景音乐		about-内容主题		numberOfPlayers-玩家人数		gameDimensions-游戏画面		gameEngine-游戏引擎		grade-游戏分级		latestVersion-最新版本		softwareSize-最新版本大小		publishStage-发行阶段		numberOfEndings-结局数		majorRole-主要角色|
|交通|交通工具|name-中文名		foreignName-外文名		powerSource-动力来源|
|交通|桥梁|name-中文名		foreignName-外文名		dateOfCommencement-始建时间		dateOfOpening-投用时间		affiliatedRegion-所属地区		type-类型		length-长度		width-宽度|
|科技|药品|name-药品名称		foreignName-外文名		alternateName-别名		isPrescription-是否处方药		indication-主要适用症		contraindication-主要用药禁忌		formulationType-剂型		athletesUseWithCaution-运动员慎用		isInsuranceMedicine-是否纳入医保		approvalNumber-批准文号		drugType-药品类型|
|艺术|电视剧作品|name-中文名		foreignName-外文名		alternateName-别名		type-类型		presenterCompany-出品公司		producerRegion-制片地区		filmingLocation-拍摄地点		publisherCompany-发行公司		dateOfRelease-首播时间		director-导演		scriptwriter-编剧		producer-制片人		starring-主演		numberOfEpisodes-集数		runningTime-每集长度		majorPrize-主要奖项		onlinePlayingPlatform-在线播放平台|
|生活|港口口岸|name-中文名		foreignName-外文名		dateOfCommencement-始建时间		dateOfOpening-投用时间		portCode-港口代码		affiliatedRegion-所属地区		waterArea-水域面积|
|艺术|艺术品|name-中文名		foreignName-外文名		author-作者		era-创作年代		classification-分类|
|人物|企业人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		nativePlace-籍贯		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		jobTitle-职务		employer-就职企业		majorAchievement-主要成就|
|艺术|纪录片|name-中文名		foreignName-外文名		alternateName-别名		type-类型		presenterCompany-出品公司		publisherCompany-发行公司		director-导演		scriptwriter-编剧		producer-制片人		numberOfEpisodes-集数		onlinePlayingPlatform-在线播放平台|
|地理|特产|name-中文名		foreignName-外文名		placeOfOrigin-产地名称|
|交通|城市公交系统|name-中文名		foreignName-外文名		busType-公交类型		affiliatedRegion-所属地区		fleetSize-车队规模		lineLength-线网长度		numberOfStations-车站数量		averageDailyPassengerThroughput-日均客运量		maximumDailyPassengerThroughput-日最高客运量		annualPassengerThroughput-年客运量		broadcastingLanguage-报站语言		ticketPrice-车票价格		regulation-管理规章		operatingOrganization-运营机构|
|文化|姓氏|name-中文名		foreignName-外文名		wayOfAcquisition-得姓方式		firstAncestor-得姓始祖 		nobleFamily-主要郡望		familyHallName-主要堂号|
|娱乐|纪录片|name-中文名		foreignName-外文名		alternateName-别名		type-类型		presenterCompany-出品公司		publisherCompany-发行公司		director-导演		scriptwriter-编剧		producer-制片人		numberOfEpisodes-集数		onlinePlayingPlatform-在线播放平台|
|生活|城市公交线路|name-中文名		foreignName-外文名		dateOfOpening-开通日期		operationalStatus-运营状态		busType-公交类型		lineLength-线路长度		numberOfStations-车站数量		terminal-起止站点		firstAndLastTimeOfStartStation-起点首末班时间		firstAndLastTimeOfEndStation-终点首末班时间		ticketPrice-车票价格		operatingOrganization-运营机构|
|地理|主题乐园|name-中文名		foreignName-外文名		address-地理位置		floorArea-占地面积		scenicLevel-景点级别		openingHours-开放时间		entranceTicketPrice-门票价格|
|生活|汽车|name-中文名		foreignName-外文名		brand-所属品牌		brakeType-制动方式		manufacturer-生产厂商		curbWeight-车身重量 		referencePrice-参考价格		wheelbase-轴距		dimensions-车型尺寸		cargoVolume -行李箱容积		fuelConsumption-油耗		fuelCapacity-油箱容积		engineType-引擎类型		seatingCapacity-标准座位数		maxSpeed-最高时速		seatMaterial-座位材质		accelerationTime-加速时间		drivetrain-驱动方式|
|文化|汉字|name-中文名		pinyin-拼音		traditionalChineseCharacter-繁体		radical-部首		inputCode-字码		wubiInputCode-五笔		cangjieInputCode-仓颉		zhengmaInputCode-郑码		strokeOrder-笔顺		characterLevel-字级		pingShuiYun-平水韵|
|生活|楼盘|name-中文名		foreignName-外文名		alternateName-别名		city-城市		district-城区		community-板块		ringPosition-环线位置		address-楼盘地址		developer-开发商		averageUnitPrice-均价		salesStatus-销售状态		propertyCategory-物业类别		buildingType-建筑形式		buildingStructure-建筑结构		constructionArea-建筑面积		floorArea-占地面积		numberOfHouseholds-总户数		greeningRate-绿化率		floorAreaRatio-容积率		dateOnSale-开盘时间		dateOfDelivery-交房时间		decorationStatus-装修情况		apartmentArea-户型面积		propertyType-产权类型		termOfProperty-产权年限		presaleLicense-预售许可证		propertyManagementCompany-物业公司		propertyManagementFee-物业费		propertyManagementOfficeAddress-物业办公地点|
|社会|企业|name-公司名称		foreignName-外文名		industry-所属行业		dateOfEstablishment-成立时间		legalRepresentative-法定代表人		headquartersLocation-总部地点		businessScope-经营范围		companyType-公司类型		slogan-公司口号		annualTurnover-年营业额		numberOfEmployees-员工数|
|体育|其他体育|name-中文名		foreignName-外文名		alternateName-别名		origin-起源|
|娱乐|漫画作品|name-中文名		originalName-原版名称		alternateName-别名		author-作者		type-类型		original-原作者		originalWork-原作品		translator-译者		scriptwriter-剧本		painter-作画		region-地区		magazine-连载杂志		firstIssueNumber-揭载号		originalRun-连载期间		bookSeries-丛书系列		originalRelease-出版期间		numberOfVolumes-单行本册数		publisher-出版社		dateOfPublication-出版时间		numberOfPages-页数		price-定价		bookSize-开本		bookDesign-装帧		isbn-ISBN|
|娱乐|专辑|name-中文名		foreignName-外文名		language-专辑语言		singer-专辑歌手		duration-专辑时长		numberOfTracks-曲目数量		genre-音乐风格		recordCompany-唱片公司		dateOfPublication-发行日期		publishRegion-发行地区		sales-唱片销量		producer-制作人		majorPrize-获得奖项|
|交通|铁路线路|name-中文名		foreignName-外文名		dateOfOpening-开通日期		lineLength-线路长度		designSpeed-设计速度		operatingSpeed-运营速度		railwayGrade-铁路等级		terminal-起止站点|
|艺术|游戏作品|name-中文名		originalName-原版名称		alternateName-别名		gameType-游戏类型		original-原作者		originalWork-原作品		platform-游戏平台		gameSeries-所属系列		region-地区		developer-开发商		publisherCompany-发行公司		dateOfPublication-发行日期		price-游戏售价		producer-制作人		director-总监		scriptwriter-编剧		majorDubber-主要配音		backgroundMusic-背景音乐		about-内容主题		numberOfPlayers-玩家人数		gameDimensions-游戏画面		gameEngine-游戏引擎		grade-游戏分级		latestVersion-最新版本		softwareSize-最新版本大小		publishStage-发行阶段		numberOfEndings-结局数		majorRole-主要角色|
|文化|论文|name-中文名		foreignName-外文名		author-作者		keyword-关键词		dateOfPublication-发表日期|
|人物|教育人物|name-中文名		nationality-国籍		ethnicity-民族		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		educationDegree-学位/学历		occupation-职业		majorIn-专业方向		jobTitle-职务		academicMasterpiece-学术代表作		majorAchievement-主要成就|
|科技|其他科技|name-中文名		foreignName-外文名		alternateName-别名|
|生活|生活用品|name-中文名		foreignName-外文名		alternateName-别名		purpose-用途		classification-分类|
|社会|医院|name-中文名		foreignName-外文名		dateOfEstablishment-成立时间		address-地理位置		competentAuthority-主管部门		openingHours-开放时间		hospitalDean-院长		hospitalGrade-医院等级		hospitalType-医院类型		motto-医院院训		isInsuranceDesignated-医保定点		economicType-经济类型		operationNature-经营性质|
|地理|街区路|name-中文名		foreignName-外文名		address-地理位置		length-长度		startPoint-起点		endPoint-终点|
|体育|单届赛事|name-中文名		foreignName-外文名		time-举办时间		venue-举办地点		tournamentType-赛事类型		organizer-主办机构|
|人物|网络红人|name-中文名		foreignName-外文名		onlineName-网络名称		nationality-国籍		ethnicity-民族		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		occupation-职业		reasonForPopularity-走红原因|
|体育|体育设施|name-中文名		foreignName-外文名		purpose-用途		classification-分类|
|生活|娱乐活动|name-中文名		foreignName-外文名		alternateName-别名		activityType-活动类型|
|体育|赛事（总）|name-中文名		foreignName-外文名		occurrenceCycle-举办期间		venue-举办地点		tournamentType-赛事类型		organizer-主办机构|
|社会|奖项（总）|name-中文名		foreignName-外文名		alternateName-别名		dateOfEstablishment-创办时间		foundingInstitution-创办机构|
|地理|河流|name-中文名		foreignName-外文名		alternateName-别名		riverSystem-所属水系		address-地理位置		flowRegion-流经地区		source-发源地		majorTributary-主要支流		riverLength-河长		basinSize-流域面积		discharge-平均流量		drop-落差|
|艺术|电视节目|name-中文名		foreignName-外文名		alternateName-别名		country-国家/地区		type-类型		host-主持人		majorGuest-主要嘉宾		productionCompany-制作公司		dateOfRelease-首播时间		broadcastChannel-播出频道		broadcastingTime-播出时间		director-导演		runningTime-每集长度		broadcastingStatus-播出状态		onlinePlayingPlatform-在线播放平台|
|科技|检查项目|name-中文名		foreignName-外文名		classification-所属分类|
|历史|战役|name-名称		time-发生时间		location-地点		belligerents-参战方		result-结果		strength-参战方兵力		casualties-伤亡情况		majorCommander-主要指挥官|
|科技|网站|name-网站名称		alternateName-别名		founder-创始人		headquartersLocation-总部地点		dateOfRelease-上线时间		offlineDate-下线时间		organizer-主办单位		websiteType-网站类型		slogan-网站口号		icpRegistrationCode-ICP备案号|
|艺术|其他艺术|name-中文名		foreignName-外文名		alternateName-别名|
|生活|桥梁|name-中文名		foreignName-外文名		dateOfCommencement-始建时间		dateOfOpening-投用时间		affiliatedRegion-所属地区		type-类型		length-长度		width-宽度|
|交通|民用机场|name-中文名		foreignName-外文名		icaoCode-ICAO代码		iataCode-IATA代码		dateOfOpening-通航日期		affiliatedRegion-所属地区		aerodromeRefCode-飞行区等级		airportType-机场类型		administration-地区管理		terminalArea-航站楼面积		numberOfParkingBays-机位数量		runwayLength-跑道长度		numberOfAirlines-航线数量		numberOfDestinations-通航城市		annualPassengerThroughput-旅客吞吐量		annualCargoThroughput-货邮吞吐量		aircraftMovements-起降架次		operatingOrganization-运营机构|
|交通|火车站|name-中文名		foreignName-外文名		railwayStationCode-车站代码		dateOfOpening-投用日期		affiliatedRegion-所属地区		railwayStationGrade-车站等级		majorRailway-主要线路		administration-区域管理		constructionArea-建筑面积		numberOfPlatforms-站台规模		annualPassengerThroughput-年客运量		annualCargoThroughput-年货运量		address-车站地址|
|交通|港口口岸|name-中文名		foreignName-外文名		dateOfCommencement-始建时间		dateOfOpening-投用时间		portCode-港口代码		affiliatedRegion-所属地区		waterArea-水域面积|
|体育|体育项目|name-中文名		foreignName-外文名		alternateName-别名		category-类别|
|自然|星体|name-中文名		foreignName-外文名		alternateName-别名		classification-分类		discoverer-发现者		dateOfDiscovery-发现时间		mass-质量		averageDensity-平均密度		diameter-直径		surfaceTemperature-表面温度		escapeVelocity-逃逸速度		albedo-反照率		apparentMagnitude-视星等		absoluteMagnitude-绝对星等		rotationPeriod-自转周期		rightAscension-赤经		declination-赤纬		distanceFromEarth-距地距离		semiMajorAxis-半长轴		eccentricity-离心率		orbitalPeriod-公转周期		meanAnomaly-平近点角		inclination-轨道倾角		longitudeOfAscendingNode-升交点经度|
|历史|其他历史|name-中文名		foreignName-外文名		alternateName-别名|
|地理|历史遗址|name-中文名		foreignName-外文名		address-地理位置		era-所处时代		floorArea-占地面积		protectionLevel-保护级别		openingHours-开放时间|
|艺术|动画作品|name-中文名		originalName-原版名称		alternateName-别名		producerCompany-动画制作		type-类型		original-原作者		originalWork-原作品		presenterCompany-出品公司		region-地区		publisherCompany-发行公司		dateOfPublication-发行日期		characterDesigner-角色设计		director-导演		scriptwriter-编剧		animationDirector-作画监督		producer-制片人		numberOfEpisodes-集数		majorDubber-主要配音		originalChannel-首播电视台		soundtrack-音乐		originalRun-播放期间		otherChannel-其他电视台		presenter-出品人		agentPublisher-代理发行		onlinePlayingPlatform-网络播放|
|文化|传统戏剧|name-中文名		dateOfApproval-批准时间		heritageLevel-非遗级别		heritageNumber-非遗编号		declaredRegion-申报地区|
|体育|俱乐部|name-中文名		foreignName-外文名		dateOfEstablishment-创办时间		founder-创始人		foundingPlace-创办地点		sports-运动项目		majorHonor-主要荣誉		coach-现任教练|
|人物|影视幕后人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		birthPlace-出生地		dateOfBirth-出生日期		dateOfDeath-逝世日期		zodiac-星座		bloodType-血型		bodyHeight-身高		bodyWeight-体重		graduatedFrom-毕业院校		occupation-职业		agency-经纪公司		majorWorks-代表作品		majorAchievement-主要成就|
|地理|自然保护区|name-中文名		natureReserveGrade-保护区级别		address-地理位置		climaticZone-气候		area-区域面积		type-类型		protectedObject-保护对象		competentAuthority-管理单位		dateOfApproval-批准时间		approvalNumber-批准文号|
|地理|景观景点|name-中文名		foreignName-外文名		address-地理位置		climate-气候条件		openingHours-开放时间		scenicLevel-景点级别		entranceTicketPrice-门票价格		floorArea-占地面积		famousScenicSpot-著名景点|
|社会|社会活动|name-中文名		foreignName-外文名		time-活动时间|
|文化|神话传说|name-中文名		foreignName-外文名		source-来源出处|
|娱乐|动画作品|name-中文名		originalName-原版名称		alternateName-别名		producerCompany-动画制作		type-类型		original-原作者		originalWork-原作品		presenterCompany-出品公司		region-地区		publisherCompany-发行公司		dateOfPublication-发行日期		characterDesigner-角色设计		director-导演		scriptwriter-编剧		animationDirector-作画监督		producer-制片人		numberOfEpisodes-集数		majorDubber-主要配音		originalChannel-首播电视台		soundtrack-音乐		originalRun-播放期间		otherChannel-其他电视台		presenter-出品人		agentPublisher-代理发行		onlinePlayingPlatform-网络播放|
|社会|其他社会|name-中文名		foreignName-外文名		alternateName-别名|
|地理|其他地理|name-中文名		foreignName-外文名		alternateName-别名|
|社会|法律法规|name-中文名		foreignName-外文名		dateOfPromulgation-颁布时间		dateOfImplementation-实施时间		publisher-发布单位|
|娱乐|单曲|name-中文名		foreignName-外文名		album-所属专辑		duration-歌曲时长		originalSinger-歌曲原唱		lyricist-填词		composer-谱曲		arranger-编曲		genre-音乐风格		dateOfPublication-发行日期		language-歌曲语言|
|科技|科技术语|name-中文名		foreignName-外文名		affiliatedSubject-所属学科|
|文化|诗文|name-作品名称		author-作者		era-创作年代		source-作品出处		genre-作品体裁|
|文化|词语|name-中文名		foreignName-外文名		pinyin-拼音		homonym-近义词		antonym-反义词|
|体育|运动队|name-中文名		foreignName-外文名		dateOfEstablishment-成立时间		affiliatedRegion-所属地区		sports-运动项目		match-角逐赛事		ground-主场馆		owner-拥有者		coach-现任主教练		famousPlayer-知名人物		majorHonor-主要荣誉|
|社会|单届奖项|name-中文名		foreignName-外文名		alternateName-别名		dateOfEstablishment-创办时间		foundingInstitution-创办机构		awardTime-颁奖时间		awardPlace-颁奖地点|
|人物|其他人物|name-中文名		foreignName-外文名		alternateName-别名		nationality-国籍		ethnicity-民族		nativePlace-籍贯		dateOfBirth-出生日期		dateOfDeath-逝世日期		graduatedFrom-毕业院校		occupation-职业		majorAchievement-主要成就|
|地理|动植物园|name-中文名		foreignName-外文名		address-地理位置		floorArea-占地面积		scenicLevel-景点级别		openingHours-开放时间		entranceTicketPrice-门票价格|

# 总结
本项目旨在收集、整理成目前开放的Schema数据集，用于指导知识图谱构建。
