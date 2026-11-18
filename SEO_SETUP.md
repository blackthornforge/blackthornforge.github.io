# Cai dat SEO cho blackthornforge.github.io

Site da co san: robots.txt, sitemap.xml, llms.txt, trang `/dark-fantasy-android-arpg/`. Viec con lai la bao cho Google / Bing biet. Khong ai dam bao thu hang, chi giup ho tim thay site nhanh hon.

## 1. Google Search Console
1. Vao https://search.google.com/search-console, dang nhap Google.
2. Bam "Add property" > chon **URL prefix** > nhap `https://blackthornforge.github.io/` > Continue.
3. Chon cach xac minh **HTML file** (de nhat voi GitHub Pages):
   - Google cho tai 1 file dang `googleXXXX.html`. Dua file (hoac token Google cho) cho Claude, Claude se dat no o thu muc goc repo. Claude KHONG tu tao duoc token, phai la token that cua nguoi dung.
   - Commit + push, doi 1-2 phut, mo `https://blackthornforge.github.io/googleXXXX.html` thay chu la dung, roi bam **Verify**.
   - Cach khac: chon "HTML tag", copy dong `<meta name="google-site-verification" content="...">` dua cho Claude de dan vao `<head>` cua `index.html`.
4. Giu file / the xac minh vinh vien (xoa la mat quyen).
5. **Gui sitemap**: menu "Sitemaps" > nhap `sitemap.xml` > Submit. Trang thai "Success" la xong.
6. **Yeu cau lap chi muc**: o thanh tren cung, dan URL vao "URL Inspection":
   - `https://blackthornforge.github.io/`
   - `https://blackthornforge.github.io/dark-fantasy-android-arpg/`
   Neu hien "URL is not on Google" > bam **Request indexing**. Moi ngay chi duoc vai lan. Index mat tu vai ngay den vai tuan.

## 2. Bing Webmaster Tools
1. Vao https://www.bing.com/webmasters, dang nhap.
2. Chon **Import your sites from Google Search Console** > cho phep > chon site. Khong can xac minh lai.
3. Vao "Sitemaps" kiem tra `sitemap.xml` da vao (neu chua thi Submit).

## 3. Meo them
- **Trang Google Play**: viet mo ta co cac cum tu that (dark fantasy, action RPG, 4 lop, co-op, offline), dung screenshot ro, them link website vao muc lien he nha phat trien.
- **Video trailer YouTube**: dang trailer, de link Google Play + link site trong phan mo ta, dung tieu de "Ashes of Thornfield - Free Dark Fantasy Action RPG for Android". Nhung video vao site sau cung duoc.
- **Reddit / itch.io / cong dong**: dang bai gioi thieu that (doc luat tung subreddit, khong spam, noi ro la ban phat trien). Moi bai dan link Google Play + link site tao backlink tu nhien.
- Dang bai tu tu, tra loi comment; khong mua review / backlink.
- Sau 2-4 tuan quay lai Search Console xem muc "Pages" (da index chua) va "Performance" (tu khoa nao hien).
