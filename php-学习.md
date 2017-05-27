#### 配置文件

<?phpreturn array( //'配置项'=>'配置值' 'DEFAULT_MODULE' => 'Admin', // 默认模块 //页面Trace false 'SHOW_PAGE_TRACE' =>Trace, 'TAGLIB_PRE_LOAD' => 'html' , 'URL_CASE_INSENSITIVE' => true, 'CONTROLLER_LEVEL' => 2, 'DB_TYPE' => 'mysql', // 数据库类型  // 此处为线上服务器配置 'DB_HOST' => '127.0.0.1', // 服务器地址 'DB_NAME' => 'school', // 数据库名 'DB_USER' => 'root', // 用户名 'DB_PWD' => 'root', // 密码

 'DB_PORT' => 3306, // 端口 'DB_PREFIX' => 'sch_', // 数据库表前缀 'DB_CHARSET'=> 'utf8', // 字符集 'DB_DEBUG' => TRUE, // 数据库调试模式 开启后可以记录SQL日志 3.2.3新增 'DATA_CACHE_TYPE'=>'file',//设置缓存方式为file 'DATA_CACHE_TIME'=>'6000',//缓存周期600秒

 //报警类型 'BAOJING_TYPE' => array(1=>'SOS报警',2=>'换卡提醒',3=>'低电提醒',4=>'盲区提醒',5=>'开机提醒',6=>'关机提醒',7=>'卫星定位'), //考试类型 'EXAM_TYPE' => array(1=>'单元测试',2=>'周考',3=>'月考',4=>'期中考试',5=>'期末考试',0=>'其它考试'), //请假类型 'LEAVE_TYPE' => array(1=>'事假',2=>'病假',0=>'其它'), //请假审批状态 'LEAVE_STATUS' => array(1=>'已批准',2=>'已驳回',0=>'已提交'), //奖励类型 'REWARD_TYPE' => array(1=>'班级奖励',2=>'年级奖励',3=>'校级奖励',4=>'市级奖励',5=>'省级奖励',6=>'国家奖励'), //关系 学生与家长 'RELATION' => array(1=>'爸爸',2=>'妈妈',3=>'爷爷',4=>'奶奶',5=>'外公',6=>'外婆',0=>'其它'), //学历 'EDUCATION' =>array(1=>'初中',2=>'中技',3=>'高中',4=>'中专',5=>'大专',6=>'本科',7=>'硕士',8=>'EMBA',9=>'博士',0=>'其它'), 'USER_TYPE' =>array(1=>'学校管理员',2=>'系统用户',3=>'老师',4=>'家长'), //评语类型 'REMARK_TYPE' =>array(1=>'平时评语',2=>'每周评语',3=>'每月评语',4=>'期中评语',5=>'期末评语'), //日志记录类型 'RECORD_TYPE' =>array(0=>'平台',1=>'APP'), 'SEX_TYPE' =>array(0=>'女',1=>'男'), 'DEVICE' =>array(0=>'未绑定',1=>'已绑定'), //消息类型 'MESSAGE_TYPE' =>array(1=>'系统消息',2=>'公告',3=>'私信'), //紧急程度 'URGENCY' => array( 1=>'普通',2=>'紧急' ), //进出校状态 'SCHOOL_TYPE' => array(0=>'进校',1=>'出校'), //签到状态 'SIGNIB_TYPE' => array(0=>'异常',1=>'正常'), //设备状态 'DEVICE_TYPE' => array(0=>'离线',1=>'在线'),  //定位类型 'TYPE' => array(0=>'GPS',1=>'LBS'),

 );
