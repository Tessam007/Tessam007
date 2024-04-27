- 👋 Hi, I’m @Tessam007
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Tessam007/Tessam007 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<odoo>
<data>
<record id="hr_attendance_view_form_inherit_odoo_biometric_attendance" model="ir.ui.view">
<field name="name">hr.attendance.view.form.inherit.odoo_biometric_attendance</field>
<field name="model">hr.attendance</field>
<field name="inherit_id" ref="hr_attendance.hr_attendance_view_form"/>
<field name="arch" type="xml">
<xpath expr="//field[@name='employee_id']" position="before">
<field name="biometric_device_id"/>
</xpath>
</field>
</record>
</data>
</odoo>
