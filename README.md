InitCode:
  Title: Kullanıcıyı Başlat
  PreHeader: Kullanıcıyı Başlat
  Subject: Kullanıcıyı Başlat
  Greeting: Merhaba {{.DisplayName}},
  Text: Bu kullanıcı oluşturuldu. Giriş yapmak için {{.PreferredLoginName}} kullanıcı adını kullanabilirsiniz. Başlatma işlemini tamamlamak için aşağıdaki düğmeye tıklayın. (Kod {{.Code}}) Bu e-postayı siz talep etmediyseniz, lütfen dikkate almayın.
  ButtonText: Başlatmayı tamamla
PasswordReset:
  Title: Şifreyi Sıfırla
  PreHeader: Şifreyi Sıfırla
  Subject: Şifreyi Sıfırla
  Greeting: Merhaba {{.DisplayName}},
  Text: Bir şifre sıfırlama isteği aldık. Şifrenizi sıfırlamak için lütfen aşağıdaki düğmeyi kullanın. (Kod {{.Code}}) Bu e-postayı siz talep etmediyseniz, lütfen dikkate almayın.
  ButtonText: Şifreyi sıfırla
VerifyEmail:
  Title: E-postayı Doğrula
  PreHeader: E-postayı Doğrula
  Subject: E-postayı Doğrula
  Greeting: Merhaba {{.DisplayName}},
  Text: Yeni bir e-posta adresi eklendi. Lütfen e-postanızı doğrulamak için aşağıdaki düğmeyi kullanın. (Kod {{.Code}}) Yeni bir e-posta eklemediyseniz, lütfen bu e-postayı dikkate almayın.
  ButtonText: E-postayı doğrula
VerifyPhone:
  Title: Telefonu Doğrula
  PreHeader: Telefonu Doğrula
  Subject: Telefonu Doğrula
  Greeting: Merhaba {{.DisplayName}},
  Text: Yeni bir telefon numarası eklendi. Lütfen doğrulamak için şu kodu kullanın: {{.Code}}
  ButtonText: Telefonu doğrula
VerifyEmailOTP:
  Title: Tek Kullanımlık Şifreyi Doğrula
  PreHeader: Tek Kullanımlık Şifreyi Doğrula
  Subject: Tek Kullanımlık Şifreyi Doğrula
  Greeting: Merhaba {{.DisplayName}},
  Text: Lütfen aşağıdaki tek kullanımlık şifreyi {{.OTP}} sonraki beş dakika içinde doğrulama için kullanın veya "Doğrula" düğmesine tıklayın.
  ButtonText: Doğrula
VerifySMSOTP:
  Text: >-
    {{.OTP}}, {{ .Domain }} için tek kullanımlık şifrenizdir. Lütfen bunu sonraki {{.Expiry}} içinde kullanın.
    
    @{{.Domain}} #{{.OTP}}
DomainClaimed:
  Title: Alan Adı Sahiplenildi
  PreHeader: E-posta / Kullanıcı Adını Değiştir
  Subject: Alan Adı Sahiplenildi
  Greeting: Merhaba {{.DisplayName}},
  Text: {{.Domain}} alan adı bir organizasyon tarafından sahiplenildi. Şu anki kullanıcı {{.Username}}, bu organizasyona ait değil. Bu nedenle giriş yaptığınızda e-posta adresinizi değiştirmeniz gerekecek. Geçici bir kullanıcı adı ({{.TempUsername}}) oluşturduk.
  ButtonText: Giriş yap
PasswordlessRegistration:
  Title: Şifresiz Giriş Ekle
  PreHeader: Şifresiz Giriş Ekle
  Subject: Şifresiz Giriş Ekle
  Greeting: Merhaba {{.DisplayName}},
  Text: Şifresiz giriş için bir token eklemek için bir istek aldık. Şifresiz giriş için cihazınızı veya tokenınızı eklemek üzere lütfen aşağıdaki düğmeyi kullanın.
  ButtonText: Şifresiz Girişi Ekle
PasswordChange:
  Title: Kullanıcının Şifresi Değiştirildi
  PreHeader: Şifreyi Değiştir
  Subject: Kullanıcının Şifresi Değiştirildi
  Greeting: Merhaba {{.DisplayName}},
  Text: Kullanıcınızın şifresi değiştirildi. Bu değişikliği siz yapmadıysanız, şifrenizi hemen sıfırlamanızı öneririz.
  ButtonText: Giriş yap
InviteUser:
  Title: {{.ApplicationName}}'e Davet
  PreHeader: {{.ApplicationName}}'e Davet
  Subject: {{.ApplicationName}}'e Davet
  Greeting: Merhaba {{.DisplayName}},
  Text: Kullanıcınız {{.ApplicationName}}'e davet edildi. Davet sürecini tamamlamak için lütfen aşağıdaki düğmeye tıklayın. Bu e-postayı siz talep etmediyseniz, lütfen dikkate almayın.
  ButtonText: Daveti kabul et
