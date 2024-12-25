unit Unit11;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls;

type
  TForm1 = class(TForm)
    Ka: TEdit;
    Kc: TEdit;
    Kb: TEdit;
    Label1: TLabel;
    Label2: TLabel;
    Label3: TLabel;
    Label4: TLabel;
    Label5: TLabel;
    Button1: TButton;
    Ex1: TEdit;
    Ex2: TEdit;
    Label6: TLabel;
    Label7: TLabel;
    Label8: TLabel;
    Label9: TLabel;
    Label10: TLabel;
    Label11: TLabel;
    procedure Button1Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;
  a,b,c,d,x1,x2: real;
implementation

{$R *.dfm}

procedure TForm1.Button1Click(Sender: TObject);
begin
  a:=StrToFloat(Ka.Text);
  b:=StrToFloat(Kb.Text);
  c:=StrToFloat(Kc.Text);
  d:=sqr(b)-4*a*c;
  if d>=0 then
          begin
            x1:=(-b+sqrt(d))/(2*a);
            x2:=(-b-sqrt(d))/(2*a);
            Ex1.Text:=FloatToStr(x1);
            Ex2.Text:=FloatToStr(x2);
          end
     else
        begin
           Ex1.Text:='Действительных корней нет';
           Ex2.Text:='Действительных корней нет';

        end;

end;

end.
