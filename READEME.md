清单配置文件.xml  注册provider
url：contents://包名/表名

raw_contacts 联系人表

contact_id  联系人唯一性id值

data  用户信息表
        raw_contact_id 外键（和上面两个表关联）
        data1   包含联系人和
        mimetype_id包含了当前行data1对应的数据类型
        
mimetypes 和data的mimetype_id做关联信息类型查询
        