# royal_home.tj
Продажа квартиры и дома в Душанбе
export default function RoyalHomeTJ() {
            </div>
          </div>
        </div>
      </section>

      {/* FOOTER */}
      <footer
        id="contact"
        className="bg-[#011816] text-white py-16 px-6"
      >
        <div className="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-12">
          <div>
            <div className="flex items-center gap-4 mb-6">
              <img
                src="/mnt/data/RHome-Водяной знак(3).png"
                alt="logo"
                className="w-16"
              />

              <div>
                <h3 className="text-2xl font-black tracking-[3px]">
                  ROYAL HOME TJ
                </h3>
                <p className="text-zinc-400 text-sm">
                  Недвижимость Душанбе
                </p>
              </div>
            </div>

            <p className="text-zinc-400 leading-relaxed">
              Современная платформа недвижимости в Таджикистане.
            </p>
          </div>

          <div>
            <h4 className="font-black text-xl mb-5">Навигация</h4>
            <ul className="space-y-3 text-zinc-400">
              <li>Главная</li>
              <li>Объекты</li>
              <li>Добавить</li>
              <li>Контакты</li>
            </ul>
          </div>

          <div>
            <h4 className="font-black text-xl mb-5">Контакты</h4>
            <ul className="space-y-3 text-zinc-400">
              <li>📍 Душанбе</li>
              <li>📞 +992 777776001</li>
              <li>✉ royalhome.tj@gmail.com</li>
            </ul>
          </div>

          <div>
            <h4 className="font-black text-xl mb-5">Соцсети</h4>

            <div className="flex gap-4">
              {['F', 'I', 'T'].map((s, i) => (
                <div
                  key={i}
                  className="w-14 h-14 rounded-2xl bg-white/10 hover:bg-[#01665f] flex items-center justify-center font-black text-lg transition cursor-pointer"
                >
                  {s}
                </div>
              ))}
            </div>
          </div>
        </div>

        <div className="border-t border-white/10 mt-14 pt-8 text-center text-zinc-500">
          © 2025 ROYAL HOME TJ • Все права защищены.
        </div>
      </footer>
    </div>
  );
}
