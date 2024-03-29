# SDLC

Software Development Life Cycle atau Siklus pengembangan _software_, merupakan rangkaian proses yang dilakukan dalam industri _software_. 
Setiap rangkaian proses yang dilakukan mungkin saja berbeda atau sama disetiap industri _software_.

## Metode Pengembangan Software

Agile, metode ini menjalankan tahap secara berulang atau iteratif. Proses menjalankan stau putaran tahapan disebut dengan Sprint.

Berikut rangkaian proses pengembangan _software_. Rangkaian ini sifatnya fleksibel, artinya tidak selalu seperti ini.

1. Analisis
  - Rencana Bisnis/membuat BRD (Business Requirement Document)
  - Alur bisnis
  - Target user
  - User requirement
  - System Requirement
     
2. Design
  - Flowchart
  - ERD
  - Use case diagram
  - Class diagram
  - UI/UX

3. Technical Design
    - Desain UI dan Diagram: [Figma](https://figma.com)/Sketch dan [draw.io](https://draw.io)
    - Backend: [supabase.com](https://supabase.com) (layanan backend menggunakan PostgreSQL)
      - Maintenance dilakukan oleh Supabase
      - Mengurangi coding di backend dan fokus di frontend
      - Semua tabel ototamis dibuatkan RESTful API
      - Tidak dipusingkan dengan migrasi proyek database
      - Skema Visual
      - Include dengan Authentication dan Storage
    - Frontend:
      - Javascript (mostly SDM sudah bersertifikat Javascript dari [Dicoding.com](https://dicoding.com))
      - [Nuxt.js](https://nuxt.com) (framework Vue)
      - UI menggunakan [Bootstrap](https://getbootstrap.com)/Tailwind
      - Module integrasi [nuxt/supabase](https://supabase.nuxtjs.org/)
    - Deploy/hosting frontend menggunakan [Vercel](https://vercel.com)/[Netlify](https://netlify.com)

4. Architecture Review
  - Review yang sudah dibuat di poin 1 s.d 3 
     
5. Development
  - Backend:
        - Mendefinisikan tabel
        - Membuat Policy untuk setiap tabel yang RLS-nya aktif (Row Level Security)
        - Menyiapkan REST API Key 
  - Frontend: 
        - Membuat inisial proyek
        - Install dependencies/requirements
        - Slicing Design (dari Figma ke Coding)
        - (Consume data dari API)
     
6. Deployment
  - Non production 

7. Testing
  - QA
  - Performance
  - Security

8. Deploy to production
9. Launch
10. Maintenance
