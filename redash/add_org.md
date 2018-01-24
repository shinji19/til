# org追加

    app = "test"
    from redash.models import Organization, Group, db, User
    default_org = Organization(name=app, slug=app, settings={})
    admin_group = Group(name='admin', permissions=['admin', 'super_admin'], org=default_org, type=Group.BUILTIN_GROUP)
    default_group = Group(name='default', permissions=Group.DEFAULT_PERMISSIONS, org=default_org, type=Group.BUILTIN_GROUP)

    db.session.add_all([default_org, admin_group, default_group])
    db.session.commit()

