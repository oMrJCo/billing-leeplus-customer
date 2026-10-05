# LEEPLUS Sales Record
ระบบบันทึกรายการขายสำหรับ LEEPLUS

## Production V1
- Supabase กลาง: leeplus-production
- Supabase Auth: Email/Password
- ตารางแยก: billing_customers, billing_sales
- Private Storage: billing-receipts
- RLS: เฉพาะผู้ใช้ที่ login แล้ว
- Dashboard ยอดวันนี้/เดือนนี้ + กราฟ 7 วัน
- เพิ่มรายการ: วันที่ + ลูกค้า + เลขบิล + ยอดขาย + รูปบิล + หมายเหตุ
- ป้องกันเลขบิลซ้ำ
- ลูกค้า + ประวัติบิล + ยอดซื้อรวม
- รายงานช่วงวันที่ + Export CSV
- Responsive desktop/mobile

ไม่มี Product/SKU/จำนวน/ราคาต่อชิ้น

## Deploy
GitHub Pages: main / root
