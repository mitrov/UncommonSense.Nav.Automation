��# U n c o m m o n S e n s e . N a v . A u t o m a t i o n  
 P o w e r S h e l l   u t i l s   f o r   M i c r o s o f t   D y n a m i c s   N A V  
 # # # N o t e s  
 T h e s e   f u n c t i o n s   s u p p o r t   v i r t u a l l y   a l l   N A V   v e r s i o n s   -   e v e n   v e r s i o n s   t h a t   d o n ' t   h a v e   n a t i v e   P o w e r S h e l l   o r   C L I   ( c o m m a n d   l i n e   i n t e r f a c e )   s u p p o r t .   D u e   t o   t h e   t e c h n o l o g y   u s e d ,   t h e   f u n c t i o n s   w i l l   o n l y   w o r k   i n   3 2 - b i t   ( x 8 6 )   P o w e r S h e l l   e n v i r o n m e n t s .  
  
 # # # I n s t a l l a t i o n  
 C l o n e   t h e   f i l e s   t o   a   f o l d e r   c a l l e d   U n c o m m o n S e n s e . N a v . A u t o m a t i o n   i n   y o u r   m o d u l e   p a t h   ( t y p i c a l l y   ` C : \ U s e r s \ { u s e r n a m e } \ D o c u m e n t s \ W i n d o w s P o w e r S h e l l \ M o d u l e s ` )   t o   m a k e   t h e m   i n s t a n t l y   a v a i l a b l e   i n   a n y   P o w e r S h e l l   s e s s i o n .  
 # # I n d e x  
 |   C o m m a n d   |   S y n o p s i s   |  
 |   - - - - - - -   |   - - - - - - - -   |  
 |   [ C o m p i l e - N A V A p p l i c a t i o n O b j e c t ] ( # C o m p i l e - N A V A p p l i c a t i o n O b j e c t )   |   C o m p i l e s   a   N A V   a p p l i c a t i o n   o b j e c t   |  
 |   [ E x p o r t - N A V A p p l i c a t i o n O b j e c t ] ( # E x p o r t - N A V A p p l i c a t i o n O b j e c t )   |   E x p o r t s   a   N A V   o b j e c t   t o   a   d i s k   f i l e .   |  
 |   [ I m p o r t - N A V A p p l i c a t i o n O b j e c t ] ( # I m p o r t - N A V A p p l i c a t i o n O b j e c t )   |   I m p o r t s   N A V   o b j e c t s   f r o m   a   d i s k   f i l e .   |  
 |   [ G e t - N A V A p p l i c a t i o n O b j e c t I n f o ] ( # G e t - N A V A p p l i c a t i o n O b j e c t I n f o )   |   R e t r i e v e s   i n f o r m a t i o n   a b o u t   N A V   o b j e c t s   t h a t   m a t c h   t h e   o p t i o n a l   f i l t e r   c r i t e r i a   |  
 |   [ S t a r t - N A V D e b u g g e r ] ( # S t a r t - N A V D e b u g g e r )   |   S t a r t s   t h e   N A V   D e b u g g e r   |  
 |   [ G e t - N A V D e v e l o p m e n t C l i e n t ] ( # G e t - N A V D e v e l o p m e n t C l i e n t )   |   R e t r i e v e s   a   c l i e n t   o b j e c t   t h a t   r e p r e s e n t s   a   r u n n i n g   M i c r o s o f t   D y n a m i c s   N A V   d e v e l o p m e n t   c l i e n t ,     o r   a   l i s t   o f   a l l   r u n n i n g   M i c r o s o f t   D y n a m i c s   N A V   d e v e l o p m e n t   c l i e n t s .   |  
  
 < a   n a m e = " C o m p i l e - N A V A p p l i c a t i o n O b j e c t " > < / a >  
 # # C o m p i l e - N A V A p p l i c a t i o n O b j e c t  
 # # # S y n o p s i s  
 C o m p i l e s   a   N A V   a p p l i c a t i o n   o b j e c t  
 # # # S y n t a x  
 ` ` ` p o w e r s h e l l  
 C o m p i l e - N A V A p p l i c a t i o n O b j e c t   [ - C l i e n t ]   < C l i e n t >   [ - T y p e ]   < s t r i n g >   [ - I D ]   < i n t >   [ < C o m m o n P a r a m e t e r s > ]  
 ` ` `  
 # # # P a r a m e t e r s  
 # # # # C l i e n t   & l t ; C l i e n t & g t ;  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         1  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               t r u e   ( B y V a l u e ,   B y P r o p e r t y N a m e )  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # T y p e   & l t ; S t r i n g & g t ;  
         S p e c i f i e s   t h e   t y p e   o f   t h e   o b j e c t   t o   e x p o r t  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         2  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               t r u e   ( B y P r o p e r t y N a m e )  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # I D   & l t ; I n t 3 2 & g t ;  
         S p e c i f i e s   t h e   I D   o f   t h e   o b j e c t   t o   e x p o r t  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         3  
         D e f a u l t   v a l u e                                 0  
         A c c e p t   p i p e l i n e   i n p u t ?               t r u e   ( B y P r o p e r t y N a m e )  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 < a   n a m e = " E x p o r t - N A V A p p l i c a t i o n O b j e c t " > < / a >  
 # # E x p o r t - N A V A p p l i c a t i o n O b j e c t  
 # # # S y n o p s i s  
 E x p o r t s   a   N A V   o b j e c t   t o   a   d i s k   f i l e .  
 # # # S y n t a x  
 ` ` ` p o w e r s h e l l  
 E x p o r t - N A V A p p l i c a t i o n O b j e c t   [ - C l i e n t ]   < C l i e n t >   [ - P a t h ]   < s t r i n g >   [ - T y p e ]   < s t r i n g >   [ - I D ]   < i n t >   [ - F o r c e ]   [ < C o m m o n P a r a m e t e r s > ]  
 ` ` `  
 # # # P a r a m e t e r s  
 # # # # C l i e n t   & l t ; C l i e n t & g t ;  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         1  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               t r u e   ( B y V a l u e ,   B y P r o p e r t y N a m e )  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # P a t h   & l t ; S t r i n g & g t ;  
         S p e c i f i e s   t h e   f o l d e r   t o   e x p o r t   t o .  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         2  
         D e f a u l t   v a l u e                                 $ P w d  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # T y p e   & l t ; S t r i n g & g t ;  
         S p e c i f i e s   t h e   t y p e   o f   t h e   o b j e c t   t o   e x p o r t  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         3  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               t r u e   ( B y P r o p e r t y N a m e )  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # I D   & l t ; I n t 3 2 & g t ;  
         S p e c i f i e s   t h e   I D   o f   t h e   o b j e c t   t o   e x p o r t  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         4  
         D e f a u l t   v a l u e                                 0  
         A c c e p t   p i p e l i n e   i n p u t ?               t r u e   ( B y P r o p e r t y N a m e )  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # F o r c e   [ & l t ; S w i t c h P a r a m e t e r & g t ; ]  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         n a m e d  
         D e f a u l t   v a l u e                                 F a l s e  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 < a   n a m e = " I m p o r t - N A V A p p l i c a t i o n O b j e c t " > < / a >  
 # # I m p o r t - N A V A p p l i c a t i o n O b j e c t  
 # # # S y n o p s i s  
 I m p o r t s   N A V   o b j e c t s   f r o m   a   d i s k   f i l e .  
 # # # S y n t a x  
 ` ` ` p o w e r s h e l l  
 I m p o r t - N A V A p p l i c a t i o n O b j e c t   [ - C l i e n t ]   < C l i e n t >   [ - P a t h ]   < s t r i n g >   [ < C o m m o n P a r a m e t e r s > ]  
 ` ` `  
 # # # P a r a m e t e r s  
 # # # # C l i e n t   & l t ; C l i e n t & g t ;  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         1  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               t r u e   ( B y V a l u e ,   B y P r o p e r t y N a m e )  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # P a t h   & l t ; S t r i n g & g t ;  
         S p e c i f i e s   t h e   f i l e   n a m e   t o   i m p o r t  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         2  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 < a   n a m e = " G e t - N A V A p p l i c a t i o n O b j e c t I n f o " > < / a >  
 # # G e t - N A V A p p l i c a t i o n O b j e c t I n f o  
 # # # S y n o p s i s  
 R e t r i e v e s   i n f o r m a t i o n   a b o u t   N A V   o b j e c t s   t h a t   m a t c h   t h e   o p t i o n a l   f i l t e r   c r i t e r i a  
 # # # S y n t a x  
 ` ` ` p o w e r s h e l l  
 G e t - N A V A p p l i c a t i o n O b j e c t I n f o   [ - C l i e n t ]   < C l i e n t >   [ [ - T y p e F i l t e r ]   < s t r i n g > ]   [ [ - I D F i l t e r ]   < s t r i n g > ]   [ [ - N a m e F i l t e r ]   < s t r i n g > ]   [ [ - M o d i f i e d F i l t e r ]   < s t r i n g > ]   [ [ - C o m p i l e d F i l t e r ]   < s t r i n g > ]   [ [ - D a t e F i l t e r ]   < s t r i n g > ]   [ [ - T i m e F i l t e r ]   < s t r i n g > ]   [ [ - V e r s i o n L i s t F i l t e r ]   < s t r i n g > ]   [ < C o m m o n P a r a m e t e r s > ]  
 ` ` `  
 # # # P a r a m e t e r s  
 # # # # C l i e n t   & l t ; C l i e n t & g t ;  
          
         R e q u i r e d ?                                         t r u e  
         P o s i t i o n ?                                         1  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               t r u e   ( B y V a l u e ,   B y P r o p e r t y N a m e )  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # T y p e F i l t e r   & l t ; S t r i n g & g t ;  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         2  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # I D F i l t e r   & l t ; S t r i n g & g t ;  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         3  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # N a m e F i l t e r   & l t ; S t r i n g & g t ;  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         4  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # M o d i f i e d F i l t e r   & l t ; S t r i n g & g t ;  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         5  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # C o m p i l e d F i l t e r   & l t ; S t r i n g & g t ;  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         6  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # D a t e F i l t e r   & l t ; S t r i n g & g t ;  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         7  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # T i m e F i l t e r   & l t ; S t r i n g & g t ;  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         8  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # V e r s i o n L i s t F i l t e r   & l t ; S t r i n g & g t ;  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         9  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 < a   n a m e = " S t a r t - N A V D e b u g g e r " > < / a >  
 # # S t a r t - N A V D e b u g g e r  
 # # # S y n o p s i s  
 S t a r t s   t h e   N A V   D e b u g g e r  
 # # # D e s c r i p t i o n  
 T h i s   f u n c t i o n   o p e n s   t h e   s e s s i o n   l i s t   w i n d o w   i n   t h e   s e l e c t e d   N A V   c l i e n t .   F r o m   t h e   s e s s i o n   l i s t ,   y o u   c a n   s e l e c t   a   s e s s i o n   t o   d e b u g .  
 C o n f i g u r a t i o n s   a r e   t a k e n   f r o m   a   c o m m a - s e p a r a t e d   ( c s v )   f i l e   c a l l e d   ` c l i e n t s . t x t `   i n   t h e   m o d u l e   f o l d e r .   E a c h   l i n e   i n   t h e   f i l e   r e p r e s e n t s   a   s i n g l e   c o n f i g u r a t i o n ,   a n d  
 c o n s i s t s   o f   t h e   f o l l o w i n g   v a l u e s :  
  
 -   I D :   a   u n i q u e   I D   f o r   e a c h   c o n f i g u r a t i o n ;   t h i s   i s   t h e   v a l u e   y o u   s p e c i f y   f o r   t h e   - C o n f i g   p a r a m e t e r .  
 -   C l i e n t E x e P a t h :   t h e   f u l l   p a t h   ( i n c l u d i n g   t h e   f i l e   n a m e )   t o   t h e   M i c r o s o f t   D y n a m i c s   N A V   R o l e   T a i l o r e d   C l i e n t .  
 -   S e r v e r N a m e :   t h e   n a m e   o f   t h e   c o m p u t e r   o n   w h i c h   t h e   M i c r o s o f t   D y n a m i c s   N A V   S e r v i c e   T i e r   i s   r u n n i n g .  
 -   P o r t N o :   t h e   p o r t   n u m b e r   t h a t   t h e   M i c r o s o f t   D y n a m i c s   N A V   S e r v i c e   T i e r   i s   l i s t e n i n g   t o .  
 -   S e r v i c e I n s t a n c e N a m e :   t h e   n a m e   o f   t h e   M i c r o s o f t   D y n a m i c s   N A V   S e r v i c e   T i e r   i n s t a n c e .  
 -   C o m p a n y N a m e :   t h e   n a m e   o f   t h e   c o m p a n y   t o   u s e   d u r i n g   d e b u g g i n g .  
  
 # # # S y n t a x  
 ` ` ` p o w e r s h e l l  
 S t a r t - N A V D e b u g g e r   - C o n f i g   < s t r i n g >   [ < C o m m o n P a r a m e t e r s > ]  
 ` ` `  
 # # # P a r a m e t e r s  
 < a   n a m e = " G e t - N A V D e v e l o p m e n t C l i e n t " > < / a >  
 # # G e t - N A V D e v e l o p m e n t C l i e n t  
 # # # S y n o p s i s  
 R e t r i e v e s   a   c l i e n t   o b j e c t   t h a t   r e p r e s e n t s   a   r u n n i n g   M i c r o s o f t   D y n a m i c s   N A V   d e v e l o p m e n t   c l i e n t ,   
 o r   a   l i s t   o f   a l l   r u n n i n g   M i c r o s o f t   D y n a m i c s   N A V   d e v e l o p m e n t   c l i e n t s .  
 # # # S y n t a x  
 ` ` ` p o w e r s h e l l  
 G e t - N A V D e v e l o p m e n t C l i e n t   - C o n f i g N a m e   < s t r i n g >   [ - F o r c e ]   [ - W i n d o w S t y l e   < s t r i n g > ]   [ < C o m m o n P a r a m e t e r s > ]  
  
 G e t - N A V D e v e l o p m e n t C l i e n t   [ - D a t a b a s e S e r v e r T y p e   < s t r i n g > ]   [ - D a t a b a s e S e r v e r N a m e   < s t r i n g > ]   [ - D a t a b a s e N a m e   < s t r i n g > ]   [ - L i s t ]   [ < C o m m o n P a r a m e t e r s > ]  
 ` ` `  
 # # # P a r a m e t e r s  
 # # # # D a t a b a s e S e r v e r T y p e   & l t ; S t r i n g & g t ;  
         F i l t e r s   r u n n i n g   c l i e n t s   b y   s e r v e r   t y p e  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         n a m e d  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # D a t a b a s e S e r v e r N a m e   & l t ; S t r i n g & g t ;  
         F i l t e r s   r u n n i n g   c l i e n t s   b y   s e r v e r   n a m e  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         n a m e d  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # D a t a b a s e N a m e   & l t ; S t r i n g & g t ;  
         F i l t e r s   r u n n i n g   c l i e n t s   b y   d a t a b a s e   n a m e  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         n a m e d  
         D e f a u l t   v a l u e                                  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # F o r c e   [ & l t ; S w i t c h P a r a m e t e r & g t ; ]  
         O p e n s   t h e   s p e c i f i e d   c o n f i g u r a t i o n   i f   i t   i s   n o t   r u n n i n g   y e t  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         n a m e d  
         D e f a u l t   v a l u e                                 F a l s e  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # W i n d o w S t y l e   & l t ; S t r i n g & g t ;  
         C o n t r o l s   h o w   t h e   d e v e l o p m e n t   c l i e n t   w i n d o w   i s   d i s p l a y e d  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         n a m e d  
         D e f a u l t   v a l u e                                 N o r m a l  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # # L i s t   [ & l t ; S w i t c h P a r a m e t e r & g t ; ]  
         R e t u r n   a l l   r u n n i n g   d e v e l o p m e n t   c l i e n t s ,   i n s t e a d   o f   o n l y   t h e   f i r s t   m a t c h  
          
         R e q u i r e d ?                                         f a l s e  
         P o s i t i o n ?                                         n a m e d  
         D e f a u l t   v a l u e                                 F a l s e  
         A c c e p t   p i p e l i n e   i n p u t ?               f a l s e  
         A c c e p t   w i l d c a r d   c h a r a c t e r s ?     f a l s e  
 # # # L i c e n s e  
 T h i s   p r o j e c t   i s   l i c e n s e d   u n d e r   t h e   A p a c h e   2 . 0   L i c e n s e .   P l e a s e   r e f e r   t o   L I C E N S E . m d   f o r   m o r e   i n f o r m a t i o n .  
  
 # # # A c k n o w l e d g e m e n t s  
 T h e s e   f u n c t i o n s   u s e   t h e   C S i d e   I n t e g r a t i o n   U t i l i t i e s   l i b r a r y   w r i t t e n   b y   T h a d d e u s   R y k e r ,   l i c e n s e d   u n d e r   t h e   A p a c h e   2 . 0   L i c e n s e .   T h e   s o u r c e   i s   o b t a i n a b l e   a t   h t t p : / / c o d e . e d g e r u n n e r . o r g / d y n a m i c s - n a v - c l i e n t - i n t e r f a c e - l i b r a r y .    
  
 D y n a m i c s   N a v   i s   a   r e g i s t e r e d   t r a d e m a r k   o f   t h e   M i c r o s o f t   C o r p o r a t i o n .  
 < d i v   s t y l e = ' f o n t - s i z e : s m a l l ;   c o l o r :   # c c c ' > G e n e r a t e d   0 4 - 0 9 - 2 0 1 5   1 5 : 0 3 : 5 1 < / d i v >  
 

[![Join the chat at https://gitter.im/jhoek/UncommonSense.Nav.Automation](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jhoek/UncommonSense.Nav.Automation?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)