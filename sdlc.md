# SDLC

Software Development Life Cycle atau Siklus pengembangan _software_, merupakan rangkaian proses yang dilakukan dalam industri _software_. 
Setiap rangkaian proses yang dilakukan mungkin saja berbeda atau sama disetiap industri _software_.

## Metode Pengembangan Software

Agile, metode ini menjalankan tahap secara berulang atau iteratif. Proses menjalankan stau putaran tahapan disebut dengan Sprint.

Berikut rangkaian proses pengembangan _software_. Rangkaian ini sifatnya fleksibel, artinya tidak selalu seperti ini.

1. Analisis (non-teknis)
    - Rencana Bisnis/membuat BRD (Business Requirement Document)
    - System Requirement
    - Alur 
     
2. Design
    - UI/UX [Figma](https://figma.com)/Sketch
    - Prototype

3. Technical Design & Technology Stack
    - ERD 
    - Use case diagram
    - Class diagram 
    - System Requirement
    - Backend: [supabase.com](https://supabase.com) 
      - PostgreSQL
      - Auth.
      - Storage
    - Frontend:
      - [Nuxt.js](https://nuxt.com) (framework Vue)
      - [Bootstrap](https://getbootstrap.com)/Tailwind
      - Module integrasi [nuxt/supabase](https://supabase.nuxtjs.org/)
    - Version Control: Git
    - Github
    - Deploy/hosting  [Vercel](https://vercel.com)

4. Architecture Review
  - Review yang sudah dibuat di poin 3

5. Development
  - Backend:
        - Mendefinisikan tabel sesuai poin 3
        - Membuat Policy untuk setiap tabel yang RLS-nya aktif (Row Level Security)
        - Menyiapkan REST API Key
  - Frontend: 
        - Slicing Design dari poin 2
        - Membuat inisial proyek
        - Install dependencies/requirements
        - (Consume data dari API)
     
6. Non-Production Deployment

7. Testing
  - QA
  - Performance
  - Security

8. Deploy to production
9. Launch
10. Maintenance
