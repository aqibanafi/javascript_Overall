1. Variables:

var, let, const
var = assign multiple variables
let = assign value in several time
const = remian unchanged

nameing convention = always use CamelCase = myFirstName

2. Condition:
   if (condition) {
   output
   } else if (condition) {
   output
   } else {
   output
   }

3. Function:

function 'function-name' (parameter) {
function body
}

Arrow function >> const functionName = (parameters) => {
function body
}

4. Loop:
   for loop = for (let i = value; condition; i increment) {
   output
   }

5. Array:
   const studentName = ["Sojol", "Kamal", "Rahim", "Bashir"]
   const numbers = [10, 50, 30, 500, 100]

practice Problem:

1.  ফাংশন নেম দিতে হবে RadianToDegree । এই ফাংশনে প্যারামিটার হিসেবে নিবে রেডিয়ান (Radian)। তারপর সেটাকে ডিগ্রীতে (Degree) কনভার্ট করে কত ডিগ্রী (Degree) হয় সেই সংখ্যা রিটার্ন করবে। রিটার্ন করার সময় দশমিক এর পর দুই ঘর রিটার্ন করতে হবে।

        1. sample input: 10, sample output: 572.96
        2. sample input: 25, sample output: 1432.39

2.  ফাংশন নেম দিতে হবে OilPrice। এই ফাংশন তিনটা প্যারামিটার নিবে।
    প্যারামিটার হিসেবে নিবে আমি কত লিটার ডিজেল, আমি কত লিটার পেট্রোল এবং আমি কত লিটার অকটেন কিনবো

            >> প্রতি লিটার ডিজেলের এর দাম – 114 টাকা

            >> প্রতি লিটার পেট্রোল এর দাম – 130 টাকা

            >> প্রতি লিটার অকটেনের এর দাম – 135 টাকা

এখন সে যদি বিভিন্ন লিটারের ডিজেল,পেট্রোল,অকটেনের অর্ডার দেয় তাহলে টোটাল কত টাকা খরচ হবে হলো সেই সংখ্যা রিটার্ন করতে হবে।

        1. sample input: 30, 20, 10, sample output: 7370
        2. sample input: 1, 0, 2, sample output: 384

3.  একটি বড় সংখ্যাক মানুষজন পিকনিকে যাবে। বাসের সংখ্যা মানুষের সংখার উপর নির্ভর করবে। ধরুন, আমাদের বাস ও মাইক্রো আছে। প্রতিটি বাসের ক্যাপাসিটি ৫০ জন এবং প্রতিটি মাইক্রবাসের ক্যাপাসিটি ১১ জন এবং পাবলিক বাসের প্রতিটি টিকেটের মূল্য ২৫০ টাকা করে। এখন আপনাকে একটি ফাংশন লিখতে হবে যার নাম হবে PublicBusFare যেটি প্যরামিটার হিসেবে একটা সংখ্যা (কতজন যাবে) নিবে। মোট কতটাকা পাবলিক বাস ফেয়ারে যাবে সেটি আপনাকে রিটার্ন করবে।

        1. sample input: 50, sample output: 0
        2. sample input: 55, sample output: 1250
        3. sample input: 235, sample output: 500
