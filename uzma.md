next js.(cmd)
            cd desktop
            npx create-next-app@latest myname
            uzma.nextjs
            cd uzma.nextjs
            npm run dev
            npm installsupabase/supabase.js
            npm run dev

supabase 
 open supoa base on google
 login with google acc
 connect with next.js
example: logen system product user note or orders


connection
we create new file on next.js folder
.en
v.local
supabase api NEXT_PUBLIC_SUPABASE_URL=https://anyprojectid.supabase.co
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=sb_publishable_key


supabase next.js file add Install Supabase:

Example departments:
 (id,username,email,salary,location)       
 Next.js - Supabase - departments- table - Data

lib/supabase.js

import { createClient } from '@supabase/supabase-js';

export const supabase = createClient(
  process.env.NEXT_PUBLIC_SUPABASE_URL,
  process.env.NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY  
);
   
   


