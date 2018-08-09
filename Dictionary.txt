using System;
using System.Collections;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            Dictionary<int, string> hs = hashtable();
            foreach (var item in hs)
            {
                if((int)item.Key<=30)
                         Console.WriteLine(item.Key + " " + item.Value);
            }
            Console.ReadKey();
        }
           public static Dictionary<int,string> hashtable() {
            Dictionary<int, string> hash = new Dictionary<int, string>();
            hash.Add(1, "Ngày thứ nhất");
            hash.Add(2, "Ngày thứ hai ");
            hash.Add(3, "Ngày thứ ba  ");
            hash.Add(4, "Ngày thứ bốn ");
            hash.Add(5, "Ngày thứ năm ");
            hash.Add(6, "Ngày thứ sáu ");
            hash.Add(7, "Ngày thứ bảy ");
            hash.Add(8, "Ngày thứ tám ");
            hash.Add(9, "Ngày thứ chín");
            hash.Add(10, "Ngày thứ mười");
            hash.Add(11, "Ngày thứ mười một ");
            hash.Add(12, "Ngày thứ mười hai ");
            hash.Add(13, "Ngày thứ mười ba  ");
            hash.Add(14, "Ngày thứ mười bốn ");
            hash.Add(15, "Ngày thứ mười năm ");
            hash.Add(16, "Ngày thứ mười sáu ");
            hash.Add(17, "Ngày thứ mười bảy ");
            hash.Add(18, "Ngày thứ mười tám ");
            hash.Add(19, "Ngày thứ mười chín");
            hash.Add(20, "Ngày thứ hai mươi");
            hash.Add(21, "Ngày thứ hai mốt ");
            hash.Add(22, "Ngày thứ hai hai ");
            hash.Add(23, "Ngày thứ hai ba  ");
            hash.Add(24, "Ngày thứ hai bốn ");
            hash.Add(25, "Ngày thứ hai năm ");
            hash.Add(26, "Ngày thứ hai sáu ");
            hash.Add(27, "Ngày thứ hai bảy ");
            hash.Add(28, "Ngày thứ hai tám ");
            hash.Add(29, "Ngày thứ hai chín");
            hash.Add(30, "Ngày thứ ba mươi");
            hash.Add(31, "Ngày thứ ba mốt ");
            hash.Add(32, "Ngày thứ ba hai ");
            hash.Add(33, "Ngày thứ ba ba  ");
            hash.Add(34, "Ngày thứ ba bốn ");
            hash.Add(35, "Ngày thứ ba năm ");
            hash.Add(36, "Ngày thứ ba sáu ");
            hash.Add(37, "Ngày thứ ba bảy ");
            hash.Add(38, "Ngày thứ ba tám ");
            hash.Add(39, "Ngày thứ ba chín");
            hash.Add(40, "Ngày thứ bốn mươi");
            hash.Add(41, "Ngày thứ bốn mốt ");
            hash.Add(42, "Ngày thứ bốn hai ");
            hash.Add(43, "Ngày thứ bốn ba  ");
            hash.Add(44, "Ngày thứ bốn bốn ");
            hash.Add(45, "Ngày thứ bốn năm ");
            hash.Add(46, "Ngày thứ bốn sáu ");
            hash.Add(47, "Ngày thứ bốn bảy ");
            hash.Add(48, "Ngày thứ bốn tám ");
            hash.Add(49, "Ngày thứ bốn chín");
            hash.Add(50, "Ngày thứ năm mươi");
            hash.Add(51, "Ngày thứ năm mốt ");
            hash.Add(52, "Ngày thứ năm hai ");
            hash.Add(53, "Ngày thứ năm ba  ");
            hash.Add(54, "Ngày thứ năm bốn ");
            hash.Add(55, "Ngày thứ năm năm ");
            hash.Add(56, "Ngày thứ năm sáu ");
            hash.Add(57, "Ngày thứ năm bảy ");
            hash.Add(58, "Ngày thứ năm tám ");
            hash.Add(59, "Ngày thứ năm chín");
            hash.Add(60, "Ngày thứ sáu mươi");
            hash.Add(61, "Ngày thứ sáu mốt ");
            hash.Add(62, "Ngày thứ sáu hai ");
            hash.Add(63, "Ngày thứ sáu ba  ");
            hash.Add(64, "Ngày thứ sáu bốn ");
            hash.Add(65, "Ngày thứ sáu năm ");
            hash.Add(66, "Ngày thứ sáu sáu ");
            hash.Add(67, "Ngày thứ sáu bảy ");
            hash.Add(68, "Ngày thứ sáu tám ");
            hash.Add(69, "Ngày thứ sáu chín");
            hash.Add(70, "Ngày thứ bảy mươi");
            hash.Add(71, "Ngày thứ bảy mốt ");
            hash.Add(72, "Ngày thứ bảy hai ");
            hash.Add(73, "Ngày thứ bảy ba  ");
            hash.Add(74, "Ngày thứ bảy bốn ");
            hash.Add(75, "Ngày thứ bảy năm ");
            hash.Add(76, "Ngày thứ bảy sáu ");
            hash.Add(77, "Ngày thứ bảy bảy ");
            hash.Add(78, "Ngày thứ bảy tám ");
            hash.Add(79, "Ngày thứ bảy chín");
            hash.Add(80, "Ngày thứ tám mươi");
            hash.Add(81, "Ngày thứ tám mốt ");
            hash.Add(82, "Ngày thứ tám hai ");
            hash.Add(83, "Ngày thứ tám ba  ");
            hash.Add(84, "Ngày thứ tám bốn ");
            hash.Add(85, "Ngày thứ tám năm ");
            hash.Add(86, "Ngày thứ tám sáu ");
            hash.Add(87, "Ngày thứ tám bảy ");
            hash.Add(88, "Ngày thứ tám tám ");
            hash.Add(89, "Ngày thứ tám chín");
            hash.Add(90, "Ngày thứ chin mươi");
            hash.Add(91, "Ngày thứ chin mốt ");
            hash.Add(92, "Ngày thứ chin hai ");
            hash.Add(93, "Ngày thứ chin ba  ");
            hash.Add(94, "Ngày thứ chin bốn ");
            hash.Add(95, "Ngày thứ chin năm ");
            hash.Add(96, "Ngày thứ chin sáu ");
            hash.Add(97, "Ngày thứ chin bảy ");
            hash.Add(98, "Ngày thứ chin tám ");
            hash.Add(99, "Ngày thứ chin chín");
            hash.Add(100, "Ngày thứ một trăm");
            return hash;
        }
    }
}
