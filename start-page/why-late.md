# ‘ডিপ লার্নিং’ কি হাইপ? কেন এতো দেরি হলো?

> Reason shapes the future, but superstition infects the present.
>
> ― Iain M. Banks

**‘ডিপ লার্নিং’ কি হাইপ? কেন এতো দেরি হলো?**

‘ডিপ লার্নিং’ নিয়ে বইটা কিছু লিখে ফেলে রেখেছিলাম অনেকদিন। মন টানছিলো না। মেশিন লার্নিংকে কেন আলাদা করে 'ডিপ লার্নিং' বলতে হবে? ২০০৬ সালে জিওফ্রে হিন্টন একটা পেপারে দেখিয়েছিলেন কিভাবে একটা ডিপ নিউরাল নেটওয়ার্ককে ঠিকমতো ট্রেইন করলে সেটার অ্যাক্যুরেসি আসে ৯৮% এর বেশি। ব্যাপারটা ছিলো হাতের লেখা ডিজিট মেশিন নির্ভুলভাবে পড়তে পারে কিনা। এই টেকনিকটাকে ব্র্যান্ডিং করা হয়েছিলো 'ডিপ লার্নিং' হিসেবে। 

মেশিন লার্নিং প্লাটফর্ম হিসেবে সাইকিট-লার্ন নিয়ে কাজ করতে গিয়ে মাঝে মধ্যে টেন্সর-ফ্লো ফ্রেমওয়ার্ক নিয়ে ঘাঁটাঘাঁটি শুরু হয় ২০১৭ সালের শুরুর দিকে। 'এন্ড টু এন্ড' প্ল্যাটফর্ম হিসেবে ভালো তবে শুরুর দিক থেকে টেন্সর-ফ্লো ১.x এর মতো এতো কমপ্লেক্স জিনিস সহজে নিয়ে আসার রাস্তাটা বেশ কঠিন ছিলো বটে। ফাস্ট ফরওয়ার্ড ৩ বছর, এলো টেন্সর-ফ্লো ২.০। মনে আশা জাগলো। যে কারণেই হোক, শেষমেশ 'ডিপ লার্নিং' এর হাইপে গা ভাসালাম। ইচ্ছা ছিলো না, তবে বদলেছি কয়েকটা কারণে। 

১. ডিপ লার্নিং আসলে মেশিন লার্নিং থেকে আলাদা কিছু নয়। মেশিন লার্নিং এর সব বেসিক জিনিস ডিপ লার্নিং এ কাজ করবে তবে হাই-পারফরম্যান্স কম্পিউটিং এবং মিলিয়ন মিলিয়ন ডেটা নিয়ে কাজ করতে আলাদা কিছু প্ল্যাটফর্ম সঙ্গে কিছু কনসেপ্ট যোগ করা দরকার। তবে, যে জিনিসটা আমাকে এই বইটা লিখতে দেরি করিয়েছে, তা হচ্ছে - আমাদের একটা বড় সংখ্যক মেশিন লার্নিং শিক্ষার্থী বেসিক মেশিন লার্নিং নিয়ে অল্প ধারণা নিয়ে ডিপ লার্নিং ফ্রেমওয়ার্ক নিয়ে কাজ করতে চাচ্ছেন। ফলে, বেসিক ঠিক না থাকার ফলে আগ্রহ হারিয়ে ফেলছেন আস্তে আস্তে। পাইথন দিয়ে ঠিকমতো এক্সপ্লোরেটোরি ডেটা অ্যানালাইসিস \(ইডিএ\) না করতে পারায় এর ভেতরে কি হচ্ছে সেটা জানা যেতো না সহজেই।  

২. ডিপ লার্নিং ফ্রেমওয়ার্ক হিসেবে টেন্সর-ফ্লো অনেকটাই স্মার্ট। তবে,  টেন্সর-ফ্লো ১.x ফ্রেমওয়ার্ক সেরকম কাউন্টার ইন্টুইটিটিভ। মানে, শুরুতে ঢোকা বেশ কষ্টের ছিলো। ডিপ লার্নিং ফ্রেমওয়ার্ক অনেক ঝামেলার, তবে সাইকিট-লার্ন যতোটা সহজ, টেন্সর-ফ্লো এর শুরুটা সেরকম বিচ্ছিরি ছিলো। সেকারণে আলাদা হাই-লেভেল এপিআই দিয়ে ঢাকতে হতো টেন্সর-ফ্লোকে। বিচ্ছিরি হবার কারণ একটাই। বেশি ক্ষমতা দেয়া তার ব্যবহারকারীদের। আর সেটাই বাড়িয়েছে কমপ্লেক্সিটি। তবে সেটা অনেকটাই ঠিক হয়ে এসেছে নতুন মেজর রিলিজে। এটা ঠিক, অনেক দেরিতে হলেও রিলিজ হয়েছে টেন্সর-ফ্লো ২.০, যা আমাকে সাহায্য করেছে বইটাকে আবার ধরতে। ডিপ লার্নিং প্ল্যাটফর্ম হিসেবে পাইটর্চ যেভাবে পাইথনিক, সেদিক থেকে টেন্সর-ফ্লো বেশ দূরে ছিলো। 

{% hint style="info" %}
আমার কাজ হচ্ছে আপনাকে একদম বেসিক থেকে শুরু করা। এখন যতো ডিপ লার্নিং 'জার্গন' মানে কীওয়ার্ড বলবো, সেটা বোঝার চেষ্টা করার প্রয়োজন নেই। 'কীওয়ার্ড' ছাড়া শুরু  "ঝিঁঝিঁপোকার থার্মোমিটার" চ্যাপ্টার থেকে। 
{% endhint %}

৩. টেন্সর-ফ্লো ২.০  = কেরাস + পাইটর্চ + পাইথনিক মানে ইগার 'এক্সজিকিউশন' + গ্লোবাল নেমস্পেস বাদ + \(সেশন নয়, ছোট ছোট ফাংশন\) + এপিআই ক্লিনআপ +অসাধারণ প্রোডাকশন ইকোসিস্টেম + বিশাল কম্যুনিটি সাপোর্ট ইত্যাদি। \(এগুলো নিয়ে আলাপ করবো সামনে\)

৪. টেন্সর-ফ্লো মেশিন লার্নিং এবং ডিপ লার্নিং এর একটা এন্ড টু এন্ড ফ্রেমওয়ার্ক। রিসার্চ টু প্রোডাকশন। একদম। এর কমিউনিটি সাপোর্ট বেজ ভয়াবহ রকমের ভালো। কোন রকমে বুঝতে পারলে হলো, বাকিটা নিয়ে যাবে এর চমৎকার ইকোসিস্টেম। মোদ্দা কথা, মেশিন লার্নিং, ডিপ লার্নিং সবকিছু করা যাবে এক জায়গায়।  

৫. ডিপ লার্নিং একটা বিশাল বিষয়। ব্যাপারটা আরো ভেতরে যাচ্ছে দিন কে দিন। এই বইটা ডিপ লার্নিং এর বেসিক জিনিসগুলো কাভার করবে যাতে আপনি রাস্তা চেনেন। রাস্তা চিনলে আর দরকার হবে না আমাকে। 

{% hint style="info" %}
যেহেতু রাষ্ট্রযন্ত্রের সাথে আছি প্রায় ৩০ বছর ধরে, অনেকে জিজ্ঞাসা করেন - এই হাই-টেক জিনিস আমাদের লাগবে কখনো? আমার ধারণা - ব্যাপারটা শুরু হয়েছে অনেক দেশে। আমাদের দরকারি ইনফ্রাস্ট্রাকচার তৈরি হচ্ছে পাশাপাশি। আমার পার্সপেক্টিভটা বলি তাহলে। 

আমাদের যেহেতু প্রচুর ডেটা আছে সরকারে, 'মেকিং সেন্স অফ ডেটা' ধারণাটা খুব দরকার সরকারি সার্ভিস ডেলিভারি প্ল্যাটফর্মগুলোতে। কখন বন্যা হবে, কখন কোন ফ্লাইওভার দরকার, আমাদের শহরগুলোতে পানির সাপ্লাই কিভাবে মেটাবো সামনের বছরগুলোতে, আগামী বছরগুলোতে কত মানুষ বিদেশে যাবেন, কতো বৈদেশিক মুদ্রা আসবে, কতো খাদ্য শস্য আমদানি করতে হবে সামনের বছরগুলোতে  - সেটা প্রেডিক্ট করতে দরকার ডেটা এবং ডেটা অ্যানালিস্ট। সেই মানুষটা আসবে কোথা  থেকে?

এখন আসি ডেটার কথায়। ডেটা থেকে প্রজ্ঞা আসবে যখন একেকটা সরকারি তথ্যভান্ডার কথা বলবে আরেকটা তথ্যভান্ডারের সাথে। সরকারি সার্ভিসগুলোকে \(নিজস্ব ডেটাসেটগুলোকে\) একে ওপরের সাথে কথা বলতে পারতে হবে 'এপিআই' এর মাধ্যমে। এখনো সরকারি সার্ভিসগুলোতে সেই ধরণের কানেক্টিভিটি নেই বলেই আমাদেরকে ১০/১২টা ন্যাশনাল আইডি, ট্যাক্স আইডেন্টিফিকেশন নম্বর, জন্ম নিবন্ধন, সিভিল রেজিস্ট্রেশন ভাইটাল স্ট্যাটিসটিক্স এর দরকারি জিনিসগুলোর ফটোকপি জমা দিতে হয় বিভিন্ন অফিসে। যার জন্য এতো আইডেন্টিফিকেশন প্রুফিং, সেই ফটোকপিতেই জাল হবার সম্ভাবনা বেশি।

ধরা যাক, রাজস্ব বোর্ডের ট্যাক্স আইডেন্টিফিকেশন নম্বর ডেটাসেটকে সিস্টেমের মধ্যেই কথা বলতে হবে ন্যাশনাল আইডি, জন্ম নিবন্ধন, বিআরটিএ এর গাড়ি নিবন্ধন, ভূমি অফিস, বোর্ড অফ ইনভেস্টমেন্ট ডেটাসেটের সাথে। রাজউকের জমির রেজিস্ট্রেশনে করতে হবে একই কাজ। ডেটাই কথা বলবে। কবে? আমি ধারণা করছি ৩ বছরেই।

কাজ হচ্ছে। সেকারণে ডেটা থেকে ধারণা পাওয়া এতোটাই  দরকার। 
{% endhint %}

৬. আমি চেষ্টা করছিলাম বাংলাদেশ সরকারের একটা ডেটাসেট নিয়ে বইটা সাঁজাতে। সমস্যা হচ্ছে, আমরা সবসময় বিদেশী ডেটাসেট নিয়ে প্র্যাকটিস করছি দেশি ডেটাসেটের অভাবে। বাইরের দেশগুলো ইচ্ছে করে তাদের ডেটাসেট ওপেন করে রাখে যাতে রিসার্চাররা তাদের গবেষণার আউটকামগুলো সেই প্রতিষ্ঠানের কাজে লাগে। সেরকম একটা ডেটাসেট পেলেও তার জন্য যে প্রি-প্রসেসিং দরকার সেটা আমার একার পক্ষে সম্ভব নয় বলে অনেক সময় ক্ষেপন করে বইটাকে নতুন করে সাঁজিয়েছি বাংলা সেন্টিমেন্ট অ্যানালাইসিস দিয়ে। হয়তোবা ভবিষ্যতে আমাদের বাংলাদেশী কোন ডেটাসেট দিয়ে কথা হবে সামনে। 



