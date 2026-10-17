<p class="meaning">অর্থ: হে আমার রব, আমার বক্ষ প্রশস্ত করে দিন এবং আমার কাজ সহজ করে দিন।</p>
          <p class="reference">সূরা ত্ব-হা, ২০:২৫–২৬</p>
        </article>

        <article class="card">
          <h3>৭. ক্ষমা ও সাহায্যের দোয়া</h3>
          <p class="arabic" lang="ar">رَبَّنَا اغْفِرْ لَنَا ذُنُوبَنَا وَإِسْرَافَنَا فِي أَمْرِنَا</p>
          <p><b>উচ্চারণ:</b> রব্বানাগফির লানা যুনুবানা ওয়া ইসরাফানা ফি আমরিনা।</p>
          <p class="meaning">অর্থ: হে আমাদের রব, আমাদের পাপ এবং আমাদের কাজের সীমালঙ্ঘন ক্ষমা করুন।</p>
          <p class="reference">সূরা আলে ইমরান, ৩:১৪৭-এর অংশ</p>
        </article>

        <article class="card">
          <h3>৮. সঠিক পথের দোয়া</h3>
          <p class="arabic" lang="ar">اهْدِنَا الصِّرَاطَ الْمُسْتَقِيمَ</p>
          <p><b>উচ্চারণ:</b> ইহদিনাস সিরাতাল মুস্তাকিম।</p>
          <p class="meaning">অর্থ: আমাদের সরল পথ দেখান।</p>
          <p class="reference">সূরা আল-ফাতিহা, ১:৬</p>
        </article>
      </div>

      <div class="notice">
        <b>মনে রাখুন:</b> বাংলা উচ্চারণ আরবি তিলাওয়াতের বিকল্প নয়।
        প্রকাশের আগে আরবি পাঠ ও অনুবাদ নির্ভরযোগ্য উৎস থেকে যাচাই করুন।
      </div>
    </section>

    <section id="tasbih">
      <h2 class="section-title">📿 ডিজিটাল তাসবিহ</h2>
      <div class="tasbih">
        <h3>সুবহানাল্লাহ</h3>
        <p>আল্লাহর পবিত্রতা ঘোষণা করুন</p>
        <div id="count" aria-live="polite">0</div>
        <button class="count-btn" onclick="increaseCount()">+ গণনা</button>
        <button class="reset-btn" onclick="resetCount()">রিসেট</button>
      </div>
    </section>

    <section id="contact">
      <h2 class="section-title">যোগাযোগ করুন</h2>
      <div class="card contact-form">
        <p>আপনার মতামত বা পরামর্শ লিখুন।</p>
        <form onsubmit="return showMessage(event)">
          <label for="name">আপনার নাম</label>
          <input id="name" type="text" placeholder="নাম লিখুন" required>

          <label for="message">আপনার বার্তা</label>
          <textarea id="message" rows="4" placeholder="বার্তা লিখুন" required></textarea>

          <button class="submit-btn" type="submit">বার্তা পাঠান</button>
        </form>
        <p id="form-result" role="status"></p>
        <p class="reference">
          নোট: এটি ডেমো ফর্ম। বার্তা সত্যিই পাঠাতে হলে আলাদা সার্ভিস সংযুক্ত করতে হবে।
        </p>
      </div>
    </section>
  </main>

  <footer>
    <p>☪ <span>RA Islamic</span></p>
    <p>জ্ঞান অর্জন করুন, ভালো কাজ করুন, মানুষের উপকার করুন।</p>
    <p>© 2026 RA Islamic</p>
  </footer>

  <script>
    let count = 0;

    function increaseCount() {
      count++;
      document.getElementById("count").textContent = count;
    }

    function resetCount() {
      count = 0;
      document.getElementById("count").textContent = count;
    }

    function showMessage(event) {
      event.preventDefault();
      document.getElementById("form-result").textContent =
        "এটি ডেমো ফর্ম—বার্তা পাঠানো হয়নি।";
      return false;
    }
  </script>

</body>
</html>
